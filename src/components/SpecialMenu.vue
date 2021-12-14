<template>
  <div class="specials">
     <div class="specials-img">
        <img src="../assets/img/h1-img-7n.png" alt="">
     </div>
     <div class="specials-pizza">

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
</style>

