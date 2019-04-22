<template>
  <div class="profile">
    <h1>MyProfile</h1>
    <div class="content">
      <ul>
        <li v-for="(item, index) in items" :key=index>
          <div v-bind=item>
            {{item.profilecontent}}
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Profile',
    data () {
      return {
        items: [
          {profilecontent: 'Masaaki Yoda'},
          {profilecontent: 'Kanazawa Institute of Technology'},
          {profilecontent: 'aa'}
        ]
      }
    }
  }
</script>
