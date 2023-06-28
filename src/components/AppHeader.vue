<script>

import AppNavBar from './AppNavBar.vue';

export default {
    name: "AppHeader",
    components: { AppNavBar },
     

}


</script>

<template>

  <header>

    <div class="container">

      <AppNavBar/>
      
      <div class="jumbo">

        <h2>
          Hungry?
        </h2>

        <h1>
          Great Food 
      
        </h1>

        <h1>
          Delivered
        </h1>

        <button>
          VIEW OUR MENU
        </button>

      </div>

    </div>




  </header>
 


</template>

<style lang="scss" scoped>
 
 header {
  background-image: url(../assets/imgs/home-background-hero-scaled.jpg);
  height: 850px;
  width: 100%;
  background-size: 100% 850px ;
  position: relative;
 }

div.jumbo {
  margin-top: 8rem;
}

h1 {
  font-size: 5rem;
  color: white;
}

h2 {
  color: white;
  font-size: 4rem;
}






</style>
