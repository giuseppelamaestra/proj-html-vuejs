<script>
import AppPopularDish from './AppPopularDish.vue';
import AppMenuCategories from './AppMenuCategories.vue';
import AppLatestNews from './AppLatestNews.vue';
export default {
    name: 'AppMain',
    components : {
        AppPopularDish,
        AppMenuCategories,
        AppLatestNews
    }
}
</script>

<template>
  
   <section class="container">
     
     <div class="ul-container">
        <ul class="flex">
           <li>24/7 DELIVERY</li>
           <li>OVER 100 DISHES</li>
           <li>IN APP ORDERING</li>
           <li>FAST DELIVERY</li>
        </ul>
     </div>


    <AppPopularDish/>

   </section>

   <div>

    <img src="../assets/imgs/first-order-background-scaled.jpg" alt="">
   </div>


  
  <AppMenuCategories/>

  <div class="food-logo">

    <ul class="flex">
        <li>Vegetarian</li>
        <li>Gluten Free</li>
        <li>Dairy Free</li>
        <li> Keto Friendly</li>
    </ul>


  </div>
  
   <div class="ordering-app-jumbo">

   
   </div>



  <AppLatestNews/>
</template>

<style lang="scss" scoped>
  
  ul {
    list-style-type: none;
    justify-content: space-evenly;
  }

  li {
    margin-right: 2rem;
    color: black;
  }

div.ul-container {
    position: absolute;
    
    top: 100%;
    background-color: white;
    height: 100px;
    width: 1000px;
    padding: 2rem;
}

img {
    width: 100%;
    margin-top: 2rem;
}

.food-logo {
    margin-top: 5rem;
    max-width: 800px;
    margin: 0 auto;
}

div.ordering-app-jumbo{
    background-image: url('../assets/imgs/app-ordering-scaled.jpg');
    height: 500px;
    width: 100%;
    background-size: 100% 500px;
    margin-top: 4rem;
}

</style>