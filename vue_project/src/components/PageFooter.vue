<template>
  <div class="bottom">
    <!-- this whole page only exports to App.vue. It contains links and some basic styling. -->
    <footer>
      <p>Programmer resources</p>
      <ul>
        <li><a href="https://stackoverflow.com/">stackoverflow</a></li>
        <li><a href="https://www.w3schools.com/tags/">W3</a></li>
        <li><a href="https://github.com/">Git Hub</a></li>
      </ul>
    </footer>
  </div>
</template>

<script>
  export default {
    name : "PageFooter"
  }
</script>

<style lang="css" scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b966;
}

</style>