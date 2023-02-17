<template>
<div>
    <Header />
    <RouterView />
    <Home />
    <Featured />
    <Invinci />
    <Popular />
</div>
</template> 

<script setup>
import Header from './components/Header.vue'; 
import Home from './components/Home.vue';
import Featured from './components/Featured.vue';
import Invinci from './components/Invinci.vue';
import Popular from './components/Popular.vue';



</script>
<style scoped>

</style>

