<template>
<div>
    <Header />
    <RouterView />
    <Home />
    <Featured />
    <Invinci />
    <Popular />
    <Custome />
    <PopularCloth />
    <Call_to_Action />
</div>
</template> 

<script setup>
import Header from './components/Header.vue'; 
import Home from './components/Home.vue';
import Featured from './components/Featured.vue';
import Invinci from './components/Invinci.vue';
import Popular from './components/Popular.vue';
import Custome from './components/Custom.vue';
import PopularCloth from './components/PopoluarCloth.vue';
import Call_to_Action from './components/Call_to_Action.vue';

</script>
<style scoped>

</style>

