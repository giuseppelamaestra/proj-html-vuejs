<template>

    <nav>

        <img src="../assets/imgs/takeout-logo-2x-200x43.png" alt="logo">

          <ul class="flex">
             <li v-for="element in elementList">
                {{ element }}
             </li>
             
          </ul>


    </nav>


</template>

<script>
export default {
    name: 'AppNavBar',


    data() {
    return {
      elementList : [
      "Home", "Order", "Online", "About", "News", "Contact Us",
      ],
      
    }
   },
}





</script>

<style lang="scss">
ul {
    color: white;
    list-style-type: none;
}

li{
    margin-right: 2rem;
}

nav {
    display: flex;
    padding-top: 4rem;
    justify-content: space-between;
}
</style>