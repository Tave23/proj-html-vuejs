<template>
   <div class="reservation">
      <div class="container-forum">
         <!-- first forum -->
         <div class="forum d-flex">
            <select class="form-control">
               <option>1 person</option>
               <option>2 persons</option>
               <option>3 persons</option>
               <option>4 persons</option>
               <option>5 persons</option>
               <option>6 persons</option>
               <option>7 persons</option>
               <option>8 persons</option>
               <option>9 persons</option>
               <option>10 persons</option>
            </select>

            <h6>for</h6>
         </div>

         <div class="forum d-flex">
            <input type="date" id="birthday" name="birthday">

            <h6>at</h6>
         </div>

         <div class="forum">
            <select class="form-control">
               <option>12:00</option>
               <option>12:15</option>
               <option>12:30</option>
               <option>12:45</option>
               <option>13:00</option>
               <option>13:15</option>
               <option>13:30</option>
               <option>13:45</option>
               <option>14:00</option>
               <option>19:00</option>
               <option>19:15</option>
               <option>19:30</option>
               <option>19:45</option>
               <option>20:00</option>
               <option>20:15</option>
               <option>20:30</option>
               <option>20:45</option>
               <option>21:00</option>
               <option>21:15</option>
               <option>21:30</option>
               <option>21:45</option>
               <option>22:00</option>
               <option>22:15</option>
               <option>22:30</option>
               <option>22:45</option>
               <option>23:00</option>

            </select>
         </div>

         <div class="forum">
            <button type="button" class="btn btn-danger">order online</button>
         </div>
      </div>  
   </div>
</template>

<script>



export default {
   name: 'Forum',
   components:{
      
   },
   data(){
      return{
        

      }
   }
   
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

.reservation{
   height: 300px;
   width: 100vw;
   background-image: url('../assets/img/h3-background-img-3.jpg');
   background-size: contain;
   background-repeat: no-repeat;
}

.container-forum{
   height: 225px;
   width: 60%;
   margin: 0 auto;
   display: flex;
   justify-content: center;
   align-items: center;
   vertical-align: middle;
}

h6{
   margin-left: 15px;
   color: white;
   text-transform: uppercase;
}

.forum{
   width: calc(100% / 4);
   margin-right: 30px;
}

.forum select{
   width: 80%;
   padding: 5px 35px 5px 0;
}

.forum h6{
   width: 20%;
   height: 100%;
   padding-top: 10px;
   padding-left: 9px;
}

.forum input{
   width: 80%;
   padding: 5px 0px 5px 5px;
}

.btn{
   text-transform: uppercase;
   font-size: 10px;
   padding: 15px 50px;
   border-radius: 0;
   background-color: $background-button-header;
}



</style>