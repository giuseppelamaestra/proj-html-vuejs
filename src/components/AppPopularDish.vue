<template>
  
<section class="container">

    <h1>
      Our Most Popular Dish 
    </h1>

   <div class="flex card-container">

    <div class="card-menu margin">
       <img src="../assets/imgs/skin-on-fries-500x714.jpg" alt="french fries">
    </div>

    <div class="card-menu margin">
       <img src="../assets/imgs/choco-cookie-frappe-400x571.jpg" alt="smoothie">
    </div>

    <div class="card-menu">
          <img src="../assets/imgs/donut-burger-400x571.jpg" alt="donut burger">
    </div>


       <button class="order-button">
          START YOUR ORDER 
       </button>
   </div>

  


</section>





</template>

<script>
  export default {
    name : 'AppPopularDish'
  }
</script>

<style lang="scss" scoped>

h1 {
    color: black;
    font-size: 3rem;
    margin-top: 3rem;
    margin-bottom: 3rem;
    text-align: center;
}

div.card-menu{
    height: 500px;
    width: calc(100% / 3 - 1rem);
   
   margin-right: 1rem;
}

.margin {
    margin-right: 1rem; 
}

.order-button {
   margin-top: 2rem;
   
}

.card-container {
    flex-wrap: wrap;
    justify-content: center;
}

img {
    height: 100%;
    width: 100%;
     object-fit: contain;
}

</style>