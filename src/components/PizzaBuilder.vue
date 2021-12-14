<template>
   <div class="pizza-builder">

      <h2>
         GO AHEAD AND <br>
         BUILD YOUR <br>
         OWN PIZZA <br>
         WE WONT <br>
         JUDGE!
      </h2>

      <div class="bg-top-left"></div>
      <div class="bg-top-mid"></div>
      <div class="bg-top-right"></div>
      <div class="bg-mid-left"></div>
      <div class="bg-mid-mid"></div>
      <div class="bg-mid-right"></div>
      <div class="bg-low-left"></div>
      <div class="bg-low-mid"></div>
      <div class="bg-low-right"></div>
   </div>
</template>

<script>

export default {
   name: 'PizzaBuilder',
   components:{

   }
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.pizza-builder{
   width: 100vw;
   margin-top: 4px;
   display: flex;
   flex-wrap: wrap;
   position: relative;
   margin-bottom: 5px;
}

h2{
   position: absolute;
   left: 25%;
   top: 15%;
   color: white;
   font-size: 50px;
}

.bg-top-left{
   width: 8%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: bottom right;
}

.bg-top-mid{
   width: 84%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: bottom center;
}

.bg-top-right{
   width: 8%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: bottom left;
}

.bg-mid-left{
   width: 8%;
   height: 240px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: top right;
}

.bg-mid-mid{
   width: 84%;
   height: 240px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: top center;
   background-size: cover;
}

.bg-mid-right{
   width: 8%;
   height: 240px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: top left;
}

.bg-low-left{
   width: 8%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: center right;
}

.bg-low-mid{
   width: 84%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: center 70%;
   background-size: cover;
}

.bg-low-right{
   width: 8%;
   height: 100px;
   background-image: url('../assets/img/h3-background-img.jpg');
   background-position: center left;
}

</style>

