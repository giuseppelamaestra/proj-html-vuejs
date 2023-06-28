<template>

    <nav>

        <img src="../assets/imgs/takeout-logo-2x-200x43.png" alt="logo">

          <ul class="flex">
             <li>ciao</li>
             <li>ciao</li>
             <li>ciao</li>
             <li>ciao</li>
             <li>ciao</li>
          </ul>


    </nav>


</template>

<script>
export default {
    name: 'AppNavBar'
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