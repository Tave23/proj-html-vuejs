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
         <img src="../assets/svg/svg-6.svg" alt="">
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
   display: flex;
   justify-content: center;
   align-items: center;
}


</style>



