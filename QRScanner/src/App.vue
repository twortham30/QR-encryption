<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
   

    <div class="wrapper">
      <HelloWorld  />

     
    </div>
  </header>

  <RouterView />
</template>

<style>
@import '@/assets/base.css';



</style>
