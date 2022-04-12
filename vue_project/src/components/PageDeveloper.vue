<template>
  <div>
    <!-- simple developer page with a link to an email address. -->
    <p>I'm The Developer</p>  
    <p>My name is Tyler</p>
    <p>You can email me <a href="mailto:admin@referralman.ca">here</a> if you want</p>
  </div>  
</template>

<script>
  // Below here exports the PageDeveloper.vue file to App.vue
  export default {
    name : "PageDeveloper"
  }
</script>

<style scoped>
/* colours the font in the developer section */
p{
  color: red;
}
</style>