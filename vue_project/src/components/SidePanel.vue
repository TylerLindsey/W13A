<template>
    <!-- this whole page only exports to SidePanel.vue. It contains links and some basic styling. -->
  <div id="SidePanel">
    <ul>
      <p>More resources that I like in the side panel!</p>
      <li><a href="https://psychologytoday.com/">Psychology Today</a></li>
      <li><a href="https://todayifoundout.com/">Today I Found Out</a></li>
      <li><a href="https://thecrashcourse.com/">Crash Course</a></li>
    </ul>
  </div>
</template>

<script>
  export default {
    name : "SidePanel"
  }
</script>

<style scoped>
#SidePanel{
  text-align: left;
  background-color: orange;
}
</style>