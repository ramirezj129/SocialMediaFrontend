<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavComponent from './components/NavComponent.vue';

</script>

<template>

    <NavComponent/>



        <!----
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>

        --->
  

  <RouterView />
</template>

<style scoped>

</style>
