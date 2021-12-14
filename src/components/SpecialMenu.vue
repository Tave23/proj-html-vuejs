<template>
  <div class="specials">
     <!-- logo pizza + img -->
     <div class="specials-img">
        <img src="../assets/img/h1-img-7n.png" alt="">
     </div>
     <!-- menu special pizzas-->
     <div class="specials-pizza">

         <div class="specials-pizza-intro">
            <h3>specials*</h3>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br> Beatae animi eius ea enim!</p>
         </div>

         <div class="pizza pizza1">
            <h4 class="price">
               $10
            </h4>
            <h4 class="name">
               combo piccolo
            </h4>
         </div>
         <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br> Beatae animi eius ea enim!</span>
         
         <div class="pizza pizza2">
            <h4 class="price">
               $20
            </h4>
            <h4 class="name">
               combo mezzo
            </h4>
         </div>
         <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br> Beatae animi eius ea enim!</span>

         <div class="pizza pizza3">
            <h4 class="price">
               $30
            </h4>
            <h4 class="name">
               combo grande
            </h4>
         </div>
         <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br> Beatae animi eius ea enim!</span>
        
     </div>

     <div class="jumbo-menu-logo">
         <img src="../assets/svg/svg-4.svg" alt="">
      </div>
  </div>
</template>

<script>
export default {
   name: 'SpecialMenu',
   components: {
      
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.specials{
   height: 500px;
   width: 100vw;
   background-color: white;
   display: flex;
   margin: 5px 0;
}

.specials-img{
   background-image: url('../assets/img/h1-img-4.jpg');
   background-size: cover;
   width: 50%;
   height: 100%;
   display: flex;
   justify-content: center;
   align-items: center;
}

.specials-img img{
   width: 40%;
}

.specials-pizza{
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   text-transform: uppercase;
   width: 40%;
   margin: 0 auto;
   position: relative;
}

.specials-pizza span{
   color: grey;
   font-size: 10px;
   text-transform: lowercase;
   margin-left: 130px;
}

.specials-pizza-intro p{
   color: grey;
   font-size: 10px;
   text-transform: lowercase;
}

.specials-pizza-intro{
   text-align: left;
   margin-left: 20px;
}

.pizza{
   display: flex;
   margin-top: 10px;
}

.pizza2{
   margin-left: -18px;
}

.pizza .price{
   color: $color-quote-newspaper;
   margin-right: 15px;
}

.jumbo-menu-logo img{
   background-color: white;
   padding: 11px 15px;
   border-radius: 50%;
   cursor: pointer;
   transform: translateY(800%);   
   margin-right: 20px;
}

.jumbo-menu-logo img:hover{
   background-color: lightgray
}
</style>

