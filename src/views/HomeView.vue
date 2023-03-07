<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <PruebasComp />
  </div>
</template>

<script>
// @ is an alias to /src

import PruebasComp from '@/components/PruebasComp.vue';
export default {
  name: 'HomeView',
  components: {
    PruebasComp,
   
  },
  

  
}
</script>
