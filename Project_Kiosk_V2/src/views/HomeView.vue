<script setup>
// import { ref, onMounted } from 'vue';
import Video from "../components/video/video.vue";
import Category from "../components/category/Category.vue";
import MenuList from "../components/menu/01_MenuList.vue";
</script>

<template>
  <div class="body">
    <header>
      <div>
        <h1 class="custom-font"> Cafe.js </h1>
      </div> 
    </header>

    <div>
        <Video/>
    </div>
    <div>
      <Category/>
    </div>
    <div>
      <MenuList/>
    </div>


  </div>
</template>


<style>


</style>