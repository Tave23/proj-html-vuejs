<template>
  <div id="header">
     <div class="header-menu" >
        <button type="button" class="btn btn-danger">Danger</button>
     </div>
  </div>
</template>

<script>
export default {
   name: 'Header',
}
</script>

<style>

#header{
   height: 400px;
   width: 100vw;
   background-color: black;
}

.header-menu{
   width: 100%;
}

</style>