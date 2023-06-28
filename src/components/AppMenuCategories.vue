<template>
   
   <section class="container">
     
    <div class="flex Mcategories-container">

        <h1>
            Menu Categories 
        </h1>

        <button>

            view the full menu 
        </button>
    </div>

     <div class="flex cards-container">

        <div class="categories-card margin">
           <img src="../assets/imgs/appetizers-menu-background.jpg" alt="">
        </div>
        <div class="categories-card margin">
            <img src="../assets/imgs/burgers-menu-background.jpg" alt="">
        </div>
        <div class="categories-card margin">
            <img src="../assets/imgs/beverages-menu-background.jpg" alt="">
        </div>
        <div class="categories-card">
            <img src="../assets/imgs/desserts-menu-background.jpg" alt="">
        </div>
        <div class="categories-card margin">
            <img src="../assets/imgs/pizza-menu-background.jpg" alt="">
        </div>
        <div class="categories-card margin">
            <img src="../assets/imgs/sides-menu-background.jpg" alt="">
        </div>
        <div class="categories-card margin">
            <img src="../assets/imgs/specials-menu-background.jpg" alt="">
        </div>
        <div class="categories-card">
            <img src="../assets/imgs/appetizers-menu-background.jpg" alt="">
        </div>
      
     </div>


   </section>
   
</template>

<script>
export default {
    name: 'AppMenuCategories'
}
</script>

<style lang="scss" scoped>

.Mcategories-container {
    justify-content: space-between;
    margin-top: 3rem;
    margin-bottom: 3rem;
}

h1 {
    font-size: 3rem;
}

.cards-container{
    flex-wrap: wrap;
}

.categories-card {
  height: 200px;
  width: calc(100% / 4 - 1rem);
  
  margin-top: 1rem;
}

.margin {
    margin-right: 1rem;
}

img {
    
    width: 100%;
     object-fit: cover;
}
</style>