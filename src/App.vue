<template>
<div>
    <Header />
    <RouterView />
    <Home />
    <Featured />
    <Invinci />
</div>
</template> 

<script setup>
import Header from './components/Header.vue'; 
import Home from './components/Home.vue';
import Featured from './components/Featured.vue';
import Invinci from './components/Invinci.vue';



</script>
<style scoped>

</style>

