<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <tabmenu></tabmenu>
    <router-view/>
  </div>
</template>

<script>
import Tabmenu from './components/TabMenu'
export default {
  name: 'App',
  components: {
    Tabmenu
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
