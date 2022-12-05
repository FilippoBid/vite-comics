<template>
 
  <TheNavbar></TheNavbar>
  
  




</template>

<script>
  import TheNavbar from "./components/TheNavbar.vue";
  import TheShop from "./components/TheShop.vue";
  import TheFooter from "./components/TheFooter.vue";

  export default {

    components :  { TheNavbar, TheShop , TheFooter } 
    
  }
</script>

<style lang="scss">
  @use "./styles/general.scss"
  

</style>
