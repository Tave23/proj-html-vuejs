<template>
   <div class="StaffPizza">
      <!-- photo staff -->
      <div class="img-staff">
         <img src="../assets/img/h1-team-1a-700x700.jpg" alt="">
         <img src="../assets/img/h1-team-2a.jpg" alt="">
         <img src="../assets/img/h1-team-3a.jpg" alt="">
         <img src="../assets/img/h1-team-4a.jpg" alt="">
      </div>
      
      <!-- brand partner -->
      <div class="partners">
         <div class="logo-partners">
            <img src="../assets/img/h1-clients-img-4.png" alt="">
            <img src="../assets/img/h1-clients-img-3.png" alt="">
            <img src="../assets/img/h1-clients-img-1.png" alt="">
            <img src="../assets/img/h1-clients-img-2.png" alt="">
            <img src="../assets/img/h1-clients-img-5.png" alt="">
         </div>
      </div>
   </div>
</template>

<script>

export default {
   name: 'StaffPizza',
   components:{

   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.StaffPizza{
   margin-bottom: 4px;
}

.img-staff{
   display: flex;
   margin-bottom: 4px;
}

.img-staff img{
   width: 25%;
   height: auto;
}

.partners{
   width: 100vw;
   height: 250px;
   background-color: $background-jumbo-testimonial;
   display: flex;
   justify-content: center;
   align-items: center;
}

.logo-partners{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 60%;
}

.logo-partners img{
   width: calc(100% / 5);
}

</style>
