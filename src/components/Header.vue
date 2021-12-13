<template>
  <div id="header">
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
  </div>
</template>

<script>
export default {
   name: 'Header',
}
</script>

<style lang="scss" >

@import "../assets/style/vars.scss";

#header{
   height: 400px;
   width: 100vw;
   background-color: black;
   text-transform: uppercase;
}

.header-menu{
   width: 70%;
   margin: 0 auto;
   justify-content: space-between;
   line-height: 65px;
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

</style>