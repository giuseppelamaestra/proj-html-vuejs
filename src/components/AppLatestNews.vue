<template>
    
    <div class="container">

        <div class="flex news-container">

            <h1>
               Latest News
            </h1>

             <button>

                 read more news
              </button>
       </div>

        <section class="flex">

            <div class="card-news margin">
                  <img src="../assets/imgs/new-milkshake-menu-800x600.jpg" alt="">
            </div>

            <div class="card-news">
                <img src="../assets/imgs/pancake-burger-800x600.jpg" alt="">
            </div>


        </section>


    </div>


</template>

<script>
export default {
    name: 'AppLatestNews'
}
</script>

<style lang="scss" scoped>


.news-container {
    justify-content: space-between;
    margin-top: 3rem;
    margin-bottom: 3rem;
}

.card-news {
    width: calc(100% / 2 - 1rem);
   

}

.margin {
    margin-right: 1rem;
}

img {
    
    width: 100%;
    height: 100%
}


</style>