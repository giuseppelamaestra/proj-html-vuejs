<template>
  
<section class="container">

    <h1>
      Our Most Popular Dish 
    </h1>

   <div class="flex card-container">

    <div class="card-menu margin">
       <h1>
        ciaoooooo
       </h1>
    </div>

    <div class="card-menu margin">
      <h1>
        ciaooooo
      </h1>
    </div>

    <div class="card-menu">
           <h1>
            ciaooooo
           </h1>
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
    width: calc(100% / 3 - 2rem);
   background-color: aqua;
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

</style>