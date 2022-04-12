<template>
  <div>
    <SidePanel/> 
    <!-- SidePanel above places the SidePanel component here in the HTML -->
    <div>
      <p>
        Hello Everyone!
      </p>
      <p>
        I'm Learning Vue so I styled the p tags red
      </p>
    </div>
    <div>
      <p>
        Above are some popular websites
      </p>
      <h1>
        Below are some other cool resources (I styled this in App.vue)
      </h1>
    </div>
    <PageDeveloper/>
    <!-- PageDeveloper above places the PageDeveloper component here in the HTML -->

  </div>
</template>

<script>
import SidePanel from '../components/SidePanel.vue'
import PageDeveloper from '../components/PageDeveloper.vue'
// The imports above bring in the data from SidePanel and PageDeveloper (which both only export) and below is the code that exports this PageMain.vue to App.vue
export default {
  name : "PageMain",
  components: {
    SidePanel,
    PageDeveloper
  }
}
</script>
<style scoped>
/* Styles the font red and makes it bigger in the main section of the page */
p{
  color: red;
  font-size: 5vh;
}
</style>