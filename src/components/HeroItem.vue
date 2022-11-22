<template>
   <div>
     
      <header id="jumbo">

        <div>
          <img class="logo" src="./../assets/logo.png" alt="logo">
        </div>        

      </header>

   </div>
</template>
 
<script>
 export default {
   name: 'HeroItem',
 }
</script>
 
 <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
 
  #jumbo{
    background-color: #3e9972;
    height: 400px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

</style>