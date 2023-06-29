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
                           "Specials",],

        navigateList : [

               "Home", "Alternate Home", "Menu", "About", "News", "Contact us", "Cart",

        ],

        informationList : ["My Account", "Terms Of Service", "Privacy Policy"],

        hoursList : ["Mon - 10AM to 11PM", "Tue - 10AM to 11PM","Wen - 10AM to 11PM","Thu - 10AM to 11PM","Fri - 10AM to 11PM",
        "Sat - 10AM to 11PM","Sun - 10AM to 11PM",
      ],

       voucherList : []


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
             <li v-for="order in orderList" class="m-top">
              
               {{ order }}

             </li>
        
         </ul>
         <ul>
            <li>
                <h3>Navigate</h3>
             </li>
            <li v-for="navigate in navigateList" class="m-top">
               {{ navigate }}
            </li>
          
         </ul>
         <ul>
            <li>
                <h3>Information</h3>
             </li>
            <li v-for="information in informationList" class="m-top">
               {{ information }}
            </li>
          
         </ul>
         <ul>
            <li>
                <h3>Opening Hours</h3>
             </li>
            <li v-for="hours in hoursList" class="m-top">
               {{ hours }}

            </li>
          
         </ul>
         <ul>

            <li>
                <h3>Voucher</h3>
             </li>
            <li v-for="voucher in voucherList" class="m-top">
               
               {{ voucher }}


            </li>
            
         </ul>




     </div>

      <div class="container center">
         <img src="../assets/imgs/takeout-logo-2x-200x43.png" alt="logo" class="center">

         <h1 class="center">Stay in the loop</h1>
         <p class="center">Sign up to receive up to date news and offers directly in your inbox:</p>
         <div class="center m-top">
            <input type="text">
         </div>
        
         <button class="center m-top">subscribe</button>
          <div class="center">
            <ul class="flex logo-ul m-top">
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
            <li>logo</li>
         </ul>

          </div>
         
      

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
    border-bottom: solid 1px white;
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

 .logo-ul {
   justify-content: center;
  
 }

 .m-top {
   margin-top: 1rem;
 }


</style>