<script>

export default {
    name : 'AppFooter',

    data(){
      return {
         orderList : [  "Appetizers",
                        "Burgers",
                         "Pizza",
                        "Fries",
                         "Sides",
                       "Desserts",
                         "Beverages",
                           "Specials",]
      }
    }
}
</script>

<template>
 
  <footer>
     <div class="container flex ul-container">
         <ul>
             <li>
                <h3>Order Online</h3>
             </li>
             <li v-for="order in orderList">
              
               {{ order }}

             </li>
        
         </ul>
         <ul>
            <li>
                <h3>Navigate</h3>
             </li>
            <li v-for="navigate in navigateList">
               {{ navigate }}
            </li>
          
         </ul>
         <ul>
            <li>
                <h3>Information</h3>
             </li>
            <li v-for="information in informationList">
               {{ information }}
            </li>
          
         </ul>
         <ul>
            <li>
                <h3>Opening Hours</h3>
             </li>
            <li v-for="hours in hoursList">
               {{ hours }}

            </li>
          
         </ul>
         <ul>

            <li>
                <h3>Voucher</h3>
             </li>
            <li v-for="voucher in voucherList">
               
               {{ voucher }}


            </li>
            
         </ul>




     </div>

      <div class="container center">
         <img src="../assets/imgs/takeout-logo-2x-200x43.png" alt="logo" class="center">

         <h1 class="center">Stay in the loop</h1>
         <p class="center">Sign up to receive up to date news and offers directly in your inbox:</p>
         <input type="text" class="center">
         <button class="center">subscribe</button>
         <ul class="flex ">
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
         </ul>

      </div>

  </footer>

</template>

<style lang="scss" scoped>
 footer {
    background-image: url('../assets/imgs/footer-background-scaled.jpg');
    width: 100%;
    height: 800px;
    background-size: 100% 800px;
    margin-top: 4rem;
 }

 ul {
    list-style-type: none;

 }

 li {
    font-size: 1rem;
 }

 .ul-container{
      justify-content: space-between;
      padding-top: 6rem;
 }

 .center {
    text-align: center;
 }

 img {
    margin-top: 3rem;
    margin-bottom: 2rem;
 }

 h1{
    color: yellow;
    font-size: 3rem;
 }


 p {
    color: white;
    margin-bottom: 1.5rem;
    margin-top: 1.5rem;
 }
</style>