<script setup>
import MainHero from "@/components/MainHero.vue";
import Ingredients from "@/components/Ingredients.vue";
</script>

<style scoped>
.app-main{
  background-color: hsl(0, 0%, 100%);
  width:50vw;
  padding:20px 50px;
}
</style>

<template>
  <div class="app-main">
    <MainHero></MainHero>
    <Ingredients></Ingredients>
  </div>
</template>