<script setup>
import MainHero from "@/components/MainHero.vue";
import Ingredients from "@/components/Ingredients.vue";
import Instructions from "@/components/Instructions.vue";
import Nutrition from "@/components/Nutrition.vue";
import ChallengeAsset from "@/components/ChallengeAsset.vue";
</script>

<style scoped>
.app-main{
  background-color: hsl(0, 0%, 100%);
  width:50vw;
  padding:20px 50px;
}

@media screen and (max-width:880px){
  .app-main{
    width:100%;
    padding:10px 20px;
  }
}
</style>

<template>
  <div class="app-main">
    <MainHero></MainHero>
    <Ingredients></Ingredients>
    <Instructions></Instructions>
    <Nutrition></Nutrition>
    <ChallengeAsset></ChallengeAsset>
  </div>
</template>