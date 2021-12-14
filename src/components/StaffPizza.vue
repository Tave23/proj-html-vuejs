<template>
   <div class="StaffPizza">
      <!-- photo staff -->
      <div class="img-staff">
         <img src="../assets/img/h1-team-1a-700x700.jpg" alt="">
         <img src="../assets/img/h1-team-2a.jpg" alt="">
         <img src="../assets/img/h1-team-3a.jpg" alt="">
         <img src="../assets/img/h1-team-4a.jpg" alt="">
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


.img-staff{
   display: flex;
}

.img-staff img{
   width: 25%;
   height: auto;
}

</style>
