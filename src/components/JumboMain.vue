<template>
   <div class="jumbotron">

<!-- jumbo pictures -->
      <div class="jumbo-main d-flex">
         <img src="../assets/img/h3-img-1.jpg" alt="">
         <img src="../assets/img/h3-img-2.jpg" alt="">
         <img src="../assets/img/h3-img-3.jpg" alt="">
         <img src="../assets/img/h3-img-4.jpg" alt="">
      </div>

<!-- jumbo testimonial -->

      <div class="jumbo-phrase">

         <div class="jumbo-phrase-text">
            <i class="fas fa-quote-left"></i>
            <h4>
               "forget the trendy pizza shops. this hidden spot makes the best new <br> york-style pizza slice in naples"
            </h4>
            <p>
               washington post 2018
            </p>
         </div>
         
         <div class="jumbo-phrase-logo">
            <img src="../assets/svg/svg-4.svg" alt="">
         </div>
      </div>

   </div>
</template>


<script>
export default {
   name: 'Jumbo-main',
   components: {
      
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.jumbo-main{
   width: 100vw;
   height: 250px;
   background-color: white;
   padding: 3px 0;
}

.jumbo-main img{
   width: 25%;
   margin: 3px;
}

.jumbo-phrase{
   background-image: url('../assets/img/h3-testimonials-bckgrnd.jpg');
   height: 350px;
   width: 100vw;
   background-position: center;
   background-size: contain;
}

.jumbo-phrase-text{
   display: flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;
   height: 90%;
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

.jumbo-phrase-text i{
   color: $color-quote-left;
   font-size: 50px;
}

.jumbo-phrase-text h4,
.jumbo-phrase-text p{
   text-align: center;
   text-transform: uppercase;
   margin-top: 20px;
}

.jumbo-phrase-text p{
   color: $color-quote-newspaper;
   font-size: 12px;
}

</style>



