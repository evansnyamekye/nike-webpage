<template>
  
<div>
  
    <Header />
    <RouterView />
    <Featured />
    <Home />
   


</div>
</template> 

<script setup>
import Header from './components/Header.vue'; 
import Featured from './components/Featured.vue';
import Home from './components/Home.vue';


</script>
<style scoped>

</style>

