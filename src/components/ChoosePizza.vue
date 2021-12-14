<template>
   <div class="ChoosePizza">
      <!-- intro choose pizza -->
      <div class="header-pizza">
         <h6>choose your flavour</h6>
         <h2>the best pizza menu in town</h2>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga dolorum nihil <br> ab illo veritatis officia ut a nemo recusandae! Dolores?</p>
      </div>

      <div class="jumbo-phrase-logo">
         <img src="../assets/svg/svg-4.svg" alt="">
      </div>

      <!-- lista pizze -->
      <div class="list-pizza">
         <!-- single pizza div -->
         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-1a-100x100.png" alt="">
            <h3>bismark</h3>
            <div class="price">
               <span class="first-price delete">$5.00</span><span class="second-price">$30.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-2a-150x150.png" alt="">
            <h3>fiori di zucca</h3>
            <div class="price">
               <span class="first-price">$7.00</span><span class="second-price">$50.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <div class="sold">
               sold
            </div>
            <img src="../assets/img/h3-product-img-6a-100x100.png" alt="">
            <h3>valdostana</h3>
            <div class="price">
               <span class="second-price">$55.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-4a-150x150.png" alt="">
            <h3>pizza tartufata</h3>
            <div class="price">
               <span class="second-price">$45.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-5a-150x150.png" alt="">
            <h3>francescana</h3>
            <div class="price">
               <span class="second-price">$25.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-3a-150x150.png" alt="">
            <h3>campagnola</h3>
            <div class="price">
               <span class="first-price">$50.00</span><span class="second-price">$95.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-1a-100x100.png" alt="">
            <h3>diavola</h3>
            <div class="price">
               <span class="first-price delete">$5.00</span><span class="second-price">$30.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-2a-150x150.png" alt="">
            <h3>quattro formaggi</h3>
            <div class="price">
               <span class="first-price">$7.00</span><span class="second-price">$50.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <div class="sold">
               sold
            </div>
            <img src="../assets/img/h3-product-img-6a-100x100.png" alt="">
            <h3>funghi</h3>
            <div class="price">
               <span class="second-price">$55.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-4a-150x150.png" alt="">
            <h3>verdure</h3>
            <div class="price">
               <span class="second-price">$45.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <img src="../assets/img/h3-product-img-5a-150x150.png" alt="">
            <h3>pescatora</h3>
            <div class="price">
               <span class="second-price">$25.00</span>
            </div>
         </div>

         <div class="singlePizza">
            <div class="sold">
               sold
            </div>
            <img src="../assets/img/h3-product-img-3a-150x150.png" alt="">
            <h3>patatine</h3>
            <div class="price">
               <span class="first-price">$50.00</span><span class="second-price">$95.00</span>
            </div>
         </div>
         
      </div>

      <div class="jumbo-refresh-logo">
         <div class="bg-logo">
            <img src="../assets/svg/svg-10.svg" alt="">
         </div>
      </div>

   </div>
</template>

<script>

export default {
   name: 'ChoosePizza',
   components:{

   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.ChoosePizza{
   height: 500px;
}

.header-pizza{
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
}

.header-pizza h6{
   padding-top: 50px;
   text-transform: uppercase;
   color: $color-quote-newspaper;
   font-size: 10px;
}

.header-pizza h2{
   text-transform: uppercase;
}

.header-pizza p{
   text-align: center;
   color: grey;
   font-size: 12px;
}

.jumbo-phrase-logo{
   height: 10%;
   text-align: right;
   margin-top: -20px;
   padding-right: 20px;
}

.jumbo-phrase-logo img{
   background-color: white;
   padding: 11px 15px;
   border-radius: 50%;
   cursor: pointer;
}

.jumbo-phrase-logo img:hover{
   background-color: lightgray
}

.list-pizza{
   width: 100vw;
   display: flex;
   overflow-x: scroll;
   margin-bottom: 70px;
   padding-bottom: 20px;
}

.singlePizza{
   height: auto;
   min-width: 16%;
   display: flex;
   flex-direction: column;
   text-align: center;
   margin-right: 30px;
   position: relative;
   cursor:pointer;
}

.sold{
   position: absolute;
   color: white;
   background-color: $background-button-header;
   border-radius: 50%;
   padding: 13px 5px;
   text-transform: uppercase;
   right: 20px;
}

.singlePizza img{
   width: 100%;
}

.singlePizza h3{
   padding-top: 15px;
   color:$color-quote-left;
   text-transform: uppercase;
   font-size: 18px;
}

.first-price{
   color: $color-quote-newspaper;
   padding-right: 10px;
}

.second-price{
  color: $color-quote-newspaper; 
}

.delete.first-price{
   text-decoration:line-through;
   color: grey;
}

.jumbo-refresh-logo{
   width: 30px;
   height: auto;
   padding-bottom: 100px;
   position: absolute;
   cursor: pointer;
}

.bg-logo{
   background-color: #EE2852;
   position: relative;
   left: 97.5vw;
   bottom: 5px;
   width: 30px;
   padding: 3px 5px;
}

.jumbo-refresh-logo img{
   filter:  brightness(0) invert(1);
}

</style>