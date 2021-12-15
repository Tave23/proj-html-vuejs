<template>
   <div class="StaffPizza">
      <!-- photo staff -->
      <div class="img-staff">

         <div class="person">
            <img src="../assets/img/h1-team-1a-700x700.jpg" alt="">
            <div class="overlay">
               <h3>frank bailey</h3>
               <p>Kitchen Porter</p>
               <div class="social">
                  <i class="fab fa-instagram"></i><i class="fab fa-twitter"></i> <i class="fab fa-facebook-f"></i>
               </div> 
            </div>
         </div>

         <div class="person">
            <img src="../assets/img/h1-team-2a.jpg" alt="">

            <div class="overlay">
               <h3>angelina jolie</h3>
               <p>Chef</p>
               <div class="social">
                  <i class="fab fa-instagram"></i><i class="fab fa-twitter"></i> <i class="fab fa-facebook-f"></i>
               </div> 
            </div>
         </div>
         
         <div class="person">
            <img src="../assets/img/h1-team-3a.jpg" alt="">

            <div class="overlay">
               <h3>katy perry</h3>
               <p>Assistant</p>
               <div class="social">
                  <i class="fab fa-instagram"></i><i class="fab fa-twitter"></i> <i class="fab fa-facebook-f"></i>
               </div> 
            </div>
         </div>
         
         <div class="person">
            <img src="../assets/img/h1-team-4a.jpg" alt="">

            <div class="overlay">
               <h3>homer simpson</h3>
               <p>Media Manager</p>
               <div class="social">
                  <i class="fab fa-instagram"></i><i class="fab fa-twitter"></i> <i class="fab fa-facebook-f"></i>
               </div> 
            </div>
         </div>
         

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
   margin-bottom: 4px;
   display: flex;
}

.person{
   width: calc(100% / 4);
}

.img-staff .person img{
   width: 100%;
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
   cursor: pointer;
}

// hover staff photo
.overlay{
   position: absolute;
   width: 100%;
   height: 100%;
   top: 0;
   left: 0;
   justify-content: center;
   align-items: center;
   display: flex;
   visibility: hidden;
   flex-direction: column;
   transition: all 0.1s;
   color:white
}

.person{
   position: relative;
}

.person:hover .overlay{
   visibility: visible;
   background-color: $background-color-hover;
   border: 15px solid white;
}

.overlay h3{
   text-transform: uppercase;
}

.overlay i{
   padding-right: 10px;
   font-size: 15px;
   cursor: pointer;
}

.overlay p{
   text-transform: capitalize;
}



</style>
