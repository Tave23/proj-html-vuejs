<template>
  <div id="header">
     <!-- menu header -->
     <div class="header-menu d-flex align-items-center">
        <!-- bottone ordine online -->
        <button type="button" class="btn btn-danger">order online</button>
         <!-- menu centrale -->
        <ul>
           <li>
              <a href="#" class="li-logos">
                 <img src="../assets/svg/svg-0.svg" alt=""> home
               </a>
            </li>
           <li><a href="#">pages</a></li>
           <li><a href="#" class="active">menu</a></li>

           <li>
              <a href="#" id="header-logo" >
                 <img src="../assets/img/h5-logo-divided-header.png" alt="logo Don Peppe">
              </a>
            </li>

           <li><a href="#">event</a></li>
           <li><a href="#">blog</a></li>
           <li><a href="#">landing</a></li>
        </ul>
         <!-- menu di dx -->
         <ul>
            <li>
               <a href="#" class="li-logos">
                  <span>0</span>
                  <img src="../assets/svg/svg-1.svg" alt="cart"> 
                  cart
               </a>
            </li>
            <li>
               <a href="#" class="li-logos">
                  <i class="fas fa-search"></i>
                  search
               </a>
            </li>
         </ul>
     </div>

      <!-- jumbotron carousel header -->
      <div class="jumbo-header">

         <img src="../assets/img/h3-rev-img-5.png" alt="" class="jumbo-header-title">
         <img src="../assets/img/h3-rev-img-6.png" alt="" class="jumbo-header-pizza">

      </div>

      <div class="prev">prev</div>
      <div class="next">next</div>
  </div>
</template>

<script>

export default {
   name: 'Header',
   components: {
      
   }
}

</script>

<style lang="scss" >

@import "../assets/style/vars.scss";

/* // menu header */

#header{
   height: 470px;
   width: 100vw;
   background-color: $bg-color-similBlack;
   text-transform: uppercase;
   position: relative;
   overflow: hidden;
}

.header-menu{
   height: 80px;
   width: 70%;
   margin: 0 auto;
   justify-content: space-between;
   line-height: 65px;
   margin-bottom: 30px;
}

.header-menu ul li{
   list-style: none;
   padding: 0 10px;
   font-size: 12px;
}

.header-menu ul li a{
   text-decoration: none;
   color: white;
}

ul li a:hover{
   color: $hover-li-header;
}

.header-menu ul{
   display: flex;
   padding-top: 20px;
}

.active{
   color: $hover-li-header !important;
}

.li-logos img{
   width: 20px;
   /* filtro per invertire il colore */
   filter: invert(100%);
}

.li-logos span{
   margin-right: -8px;
   bottom: 5px;
   background-color: white;
   color: orange;
   border-radius: 70%;
   z-index: 99;
   position: relative;
   padding: 2px 5px;
}

#header-logo img{
   width: 100px;
}

.header-menu .btn{
   text-transform: uppercase;
   font-size: 10px;
   height: 30px;
   width: 110px;
   border-radius: 0;
   background-color: $background-button-header;
}

// jumbotron header

.jumbo-header{
   width: 60%;
   height: calc(470px - 80px - 30px);
   margin: 0 auto;
   display: flex;
   padding-bottom: 40px;
}

.jumbo-header-pizza{
   margin-left: -60%;
}

.prev{
   left: -30px;
   rotate: 90deg;
   padding: 8px 10px 30px;
}

.next{
   right: -30px;
   padding: 8px 10px 35px;
   rotate: 270deg;
}

.next,
.prev{
   border-radius: 50%;
   font-size: 13px;
   bottom: 45%;
   background-color: white;
   color: $color-quote-newspaper;
   position: absolute;
   cursor: pointer;
}
</style>