<script setup>
import ingreValues from "@/data/ingreValues.json"
</script>

<style scoped>
.ingredient-main-ctn{
    color: hsl(30, 10%, 34%);
    padding:30px 0;
    line-height:3;
}
.ingredient-main-ctn h2{
    color:hsl(14, 45%, 36%);
    font-family: "Young Serif", serif;
    font-style: normal;
    font-weight:400;
}
.ingredient-main-ctn ul{
    font-family: "Outfit", sans-serif;
    padding:0 30px;
}
</style>

<template>
    <div class="ingredient-main-ctn">
        <h2>Ingredients</h2>
        <ul v-for="ingreValue in ingreValues" :key="ingreValue.id">
            <li>{{ingreValue.content}}</li>
        </ul>
    </div>
</template>