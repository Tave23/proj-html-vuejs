<template>
   <div class="footer">
      <div class="left-side">
         <div class="container-footer">

            <div class="restaurants">
               <h6>find our restaurants</h6>

               <!-- <div class="address">
                  <p>
                     1614 E. Bell Rd #104. <br>
                     Salerno, AZ 85022 <br>
                     (602) 867-1010
                  </p>
               </div>

               <div class="address">
                  <p>
                     204 E. Piazzetta Tommaso <br>
                     Sorrento, AZ 85022 <br>
                     (358) 867-1010
                  </p>
               </div>

               <div class="address">
                  <p>
                     Viale Puglia 54 <br>
                     Torre Del Greco, AZ 85022 <br>
                     (359) 867-1010
                  </p>
               </div>

               <div class="address">
                  <p>
                     Corso Itali AA <br>
                     Naples, AZ 85022 <br>
                     (989) 867-1010
                  </p>
               </div> -->

               <div
               class="address"
               v-for="singleAddress in listAddress" :key="singleAddress">

                  <p>{{singleAddress}}</p>

               </div>
            </div>

            <div class="working-hours">
               <h6>working hours</h6>
               <div class="title">
                  <p>monday</p>
                  <span id="closed">kitchen closed</span>
               </div>
               <div class="title">
                  <p>tuesday until friday</p>
                  <span>9:00 - 22:00</span>
               </div>
               <div class="title">
                  <p>saturday</p>
                  <span>Saturday 11am to midnight</span>
               </div>
               <div class="title">
                  <p>sunday</p>
                  <span>9:00 - 22:00</span>
               </div>
               <div class="title social">
                  <p>follow us: </p><i class="fab fa-twitter"></i> <i class="fab fa-facebook-f"></i> <i class="fab fa-instagram"></i> <i class="fab fa-linkedin-in"></i>
               </div>
            </div>
            
            <div class="slogan">
               <h3>
                  the don peppe crew <br>
                  first and foremost <br>
                  values an authentic,<br>
                  well baked slice of <br>
                  pizza.
               </h3>
            </div>
         </div>

         <p class="created-by">Created with &#9825; by <span>Qode Interactive</span></p>

         <img src="../assets/img/h1-img-7n.png" alt="">
      </div>
      <div class="right-side">

         <div class="jumbo-phrase-logo">
            <img src="../assets/svg/svg-4.svg" alt="">
         </div>

      </div>
   </div>
</template>


<script>
export default {
   name: 'Footer',
   components: {
      
   },
   props:{
      listAddress: Array
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.footer{
   height: 500px;
   width: 100vw;
   display: flex;
}

.left-side{
   width: 50%;
   height: 100%;
   background-color: $bg-color-similBlack;
   padding-top: 80px;
   padding-bottom: 30px;
   position: relative;
}

.left-side img{
   position: absolute;
   bottom: 25px;
   right: 25px;
   width: 15%;
}

.right-side{
   width: 50%;
   height: 100%;
   background-image: url('../assets/img/footer-img-1.jpg');
   background-position: center;
   position: relative;
}

.container-footer{
   height: 100%;
   width: 90%;
   margin: 0 auto;
   display: flex;
}

.restaurants,
.working-hours,
.slogan{
   height: 80%;
   width: calc(100% / 3);
}

.working-hours{
   padding-left: 15px;
}

.slogan h3{
   font-size: 17px;
   font-weight: 850;
   color: white;
   text-transform: uppercase;
}

.title{
   margin-bottom: 20px;
}

.title p{
   color: $color-quote-left;
   text-transform: uppercase;
   font-size: 13px;
   font-weight: 600;
   margin-bottom: 0;
}

.title span{
   color: gray;
   font-size: 12px;
   margin-top: -10px;
}

#closed{
   color: $color-quote-newspaper !important;
}

.title.social{
   margin-top: 30px;
   display: flex;
   line-height: 1;
}

.title.social p{
   padding-right: 5px;
}

.working-hours h6,
.restaurants h6{
   color: $color-quote-left;
   font-size: 15px;
   font-weight: bolder;
   text-transform: uppercase;
   margin-bottom: 15px;
}

.social i{
   color: white;
   margin-right: 10px;
   font-size: 12px;
}

.restaurants p{
   color: gray;
   font-size: 13px;
   width: 75%;
}

.created-by{
   color: $color-quote-left;
   font-size: 10px;
   width: 90%;
   margin: 0 auto;
}

.created-by span{
   color: $Qode-interactive;
}

.jumbo-phrase-logo{
   height: 10%;
   position: absolute;
   right: 10px;
   bottom: 10px;
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
</style>