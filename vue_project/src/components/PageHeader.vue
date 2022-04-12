<template>
  <div class="top">
    <header>
      <DropDown/>
      <!-- DropDown incorporates the DropDown.vue component into it's HTML (although I couldnt get the toggle working in time, it still is there, just with display: none right now.) -->
      <p>Social Media</p>
      <ul>
        <li><a href="https://google.com/">Google</a></li>
        <li><a href="https://facebook.com/">facebook</a></li>
        <li><a href="https://youtube.com/">Youtube</a></li>
      </ul>
    </header>
    
  </div>
</template>

<script>
  import DropDown from '../components/DropDown.vue'
// Above imports the DropDown component and below exports this file to App.vue
  export default {
  name : 'PageHeader',
  components: {
    DropDown
  }
  // This includes DropDown in the export to App.vue
};
</script>

<style scoped>
/* Basic styling on Social media tags */
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #afb942;
}
p{
  color: blue;
}
</style>
