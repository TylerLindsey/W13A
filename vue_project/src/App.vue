<template>
<!-- This is the main page being exported to the web. It imports all of the files that arent exported to a different page already -->
  <div id="app">
    <PageHeader/>
    <PageMain/>
    <PageFooter/>
<!-- The 3 lines above this comment import the secondary pages that have not been exported anywhere yet. -->
  </div>
</template>

<script>
import PageFooter from './components/PageFooter.vue'
import PageHeader from './components/PageHeader.vue'
import PageMain from './components/PageMain.vue'
    // This is where App.vue imports the files it needs, and the below exports the entire project to the localhost. 

export default {
  name: 'App',
  components: {
    PageHeader,
    PageFooter,
    PageMain
  }
}
</script>

<style>
/* Basic styling of the entire site, #app aligns the items to the center and H1 sets blue on all H1 tags, and body sets the background bisque */
#app {
  text-align: center;
}
h1{
  color: blue;
}
body{
  background-color: bisque;
}
/* how everything is centered */
</style>
