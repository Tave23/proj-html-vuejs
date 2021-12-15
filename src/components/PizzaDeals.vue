<template>
   <div class="pizzaDeals">
      <!-- logo cart -->
      <div class="jumbo-cart-logo">
         <div class="bg-logo">
            <img src="../assets/svg/svg-9.svg" alt="">
         </div>
      </div>

      <!-- left img -->
      <div class="left-img">
         <div class="container-leftside">
            <!-- intro -->
            <h6>made with love</h6>
            <h3>delish pizza deals</h3>

            <!-- first date -->
            <div class="appointment">
               <div class="date">
                  <div class="day">
                     <h4>02</h4>
                  </div>
                  <div class="month">
                     <h5>nov</h5>
                  </div>
               </div>

               <div class="description">
                  <h5>traditional neapolitan pies in kyoto <br>pizza mercato</h5>
                  <p><i class="fas fa-map-marker-alt"></i> 204 E. Pizzetta Tommaso</p>
               </div>
            </div>

            <div class="line">
               <p>................................................................................................................</p>
            </div>

            <!-- second date -->
            <div class="appointment">
               <div class="date">
                  <div class="day">
                     <h4>03</h4>
                  </div>
                  <div class="month">
                     <h5>nov</h5>
                  </div>
               </div>

               <div class="description">
                  <h5>terrazza patio dining space opening<br>this weekend</h5>
                  <p><i class="fas fa-map-marker-alt"></i> 204 E. Pizzetta Tommaso</p>
               </div>
            </div>

            <div class="line">
               <p>................................................................................................................</p>
            </div>

            <!-- third date -->
            <div class="appointment">
               <div class="date">
                  <div class="day">
                     <h4>05</h4>
                  </div>
                  <div class="month">
                     <h5>nov</h5>
                  </div>
               </div>

               <div class="description">
                  <h5>sienna private dining room with <br>stéphane brunn</h5>
                  <p><i class="fas fa-map-marker-alt"></i> 204 E. Pizzetta Tommaso</p>
               </div>
            </div>
         </div>
      </div>

      <!-- right half -->
      <div class="right-img">
         <img src="../assets/img/h3-img-5a.jpg" alt="">
      </div>
   </div>
</template>


<script>
export default {
   name: 'PizzaDeals',
   components: {
      
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.pizzaDeals{
   margin-top: 120px;
   position: relative;
   display: flex;
}

.jumbo-cart-logo{
   width: 30px;
   height: auto;
   padding-bottom: 100px;
   position: absolute;
   cursor: pointer;
}

.bg-logo{
   background-color: white;
   position: relative;
   left: 97.5vw;
   top: 10px;
   width: 30px;
   padding: 3px 5px;
}

.right-img,
.left-img{
   width: 50%;
}

.right-img img{
   width: 100%;
}

.left-img{
   background-color: black;
   border-bottom: 80px solid white;
}

.container-leftside{
   width: 70%;
   margin: 0 auto;
   padding: 50px 0;
}

h3, h6, h5{
   text-transform: uppercase;
}

h6, p, h4{
   color: $color-quote-newspaper;
}

h3, h5{
   color: white;
}

.appointment{
   display: flex;
   justify-content: flex-start;
   align-items: center;
   margin: 20px 0 5px;
}

.date{
   margin-right: 40px;
}

.date h4{
   font-size: 45px;
}

.date h5{
   font-size: 35px;
   margin-top: -15px;
}

.description h5{
   font-size: 18px;
}

.description p{
   margin-top: 10px;
}

.line p{
   color: #B68A2C
}

</style>