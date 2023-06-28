<script>

import AppNavBar from './AppNavBar.vue';

export default {
    name: "AppHeader",
    components: { AppNavBar }
}


</script>

<template>

  <header>

    <div class="container">

      <AppNavBar/>


    </div>




  </header>
 


</template>

<style lang="scss" scoped>
 
 header {
  background-image: url(../assets/imgs/home-background-hero-scaled.jpg);
  height: 850px;
  width: 100%;
  background-size: 100% 850px ;
 }

</style>
