<template>
   <div class="footer">
      <div class="left-side">
         <div class="container-footer">
            <div class="restaurants">

            </div>
            <div class="working-hours">

            </div>
            <div class="slogan">

            </div>
         </div>
      </div>
      <div class="right-side"></div>
   </div>
</template>


<script>
export default {
   name: 'Footer',
   components: {
      
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

.right-side{
   width: 50%;
   height: 100%;
   background-image: url('../assets/img/footer-img-1.jpg');
   background-position: center;
}

.container-footer{
   height: 100%;
   width: 90%;
   margin: 0 auto;
   background-color: blueviolet;
   display: flex;
}

.restaurants{
   height: 80%;
   width: calc(100% / 3);
   background-color: chartreuse;
}

.working-hours{
   height: 80%;
   width: calc(100% / 3);
   background-color: teal;
}

.slogan{
   height: 80%;
   width: calc(100% / 3);
   background-color: pink;
}

</style>