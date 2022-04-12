<template>
  <div class="DropDown">
      <button onclick="dropDownMenu()" class="dropbtn">Drop Down</button>
      <div id="myDropDown" class="dropdown-content">
        <p>First sites I made</p>
          <a href="https://referralman.ca/">Referral Man</a>
          <a href="https://okpizza.tk/">OK Pizza</a>
      </div>
    </div>
    <!-- The above div is hidden by display:none in style. I could not figure out the drop down menu in time for submission.-->
</template>

<script>
  export default {
  name : "DropDown",
  }
  // Above here exports the DropDown.vue file to App.vue, below here is codes that I have commented out while I worked on making the drop down work.
  // function dropMenu(){
  //   document.getElementById('myDropDown').classList.toggle('show');
  // }
  // dropMenu();
  // function clickBtn(){
  //   document.getElementById('dropDownMenu').addEventListener('click', dropMenu)
  // }
  // clickBtn();
</script>

<style scoped>
/* Below here colours the button, changes to button colour on hover and blocks out the content in the HTML respectively. Below that is commented out while trying to figure out the hover.  */
  .dropbtn {
    background-color: rgb(237, 136, 12);
  }

  .dropbtn:hover, .dropbtn:focus{
    background-color: rgb(126, 74, 9);
  }

  .dropdown-content{
    display: none;
    z-index: 1;
  }

  /* .dropdown a:hover {
    background-color: rgb(237, 136, 12);
  }

  .show {
    display: block;
  } */
</style>