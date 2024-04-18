<script setup lang="ts">
import {defineExpose} from "vue";
import profile from "./assets/profile.jpg";

defineExpose({profile});
</script>

<template>
  <div class="flex flex-col items-center justify-center lg:justify-center lg:items-start relative h-80 lg:h-80 mx-auto p-10">
    <img :src="profile" class="w-60 h-60 lg:w-60 lg:h-60 lg:rounded-full absolute mt-5 top-0 left-1/2 transform -translate-x-1/2" />
    <h1 class="text-2xl lg:text-3xl font-bold text-white absolute bottom-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2">Hello, I'm Mek Jen Rui </h1>
  </div>
  <div class="flex flex-col items-center justify-center mb-12 mt-10 p-5 bg-white rounded shadow-lg">
    <p class="text-sm lg:text-lg text-gray-700">I enjoy sports and games, finding them both exhilarating and a great way to unwind. 
    In my free time, I love participating in various sports activities and diving into engaging games.</p>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body {
  font-family: 'Roboto', sans-serif;
}
</style>