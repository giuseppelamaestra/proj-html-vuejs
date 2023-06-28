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
           <li>ciao</li>
           <li>ciao</li>
           <li>ciao</li>
           <li>ciao</li>
        </ul>
     </div>


    <AppPopularDish/>

   </section>


  
  <AppMenuCategories/>
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


</style>