<script setup>
import instructValues from "@/data/instructValues.json";
</script>

<style scoped>
.instruction-main-ctn{
    color: hsl(30, 10%, 34%);
    padding:30px 0;
    line-height:3;
}
.instruction-main-ctn h2{
    color:hsl(14, 45%, 36%);
    font-family: "Young Serif", serif;
    font-style: normal;
    font-weight:400;
}
.instruction-main-ctn div{
    font-family: "Outfit", sans-serif;
    padding:0 10px;
    text-align:justify;
}
</style>

<template>
    <div class="instruction-main-ctn">
        <h2>Instructions</h2>
        <div v-for="instructValue in instructValues" :key="instructValue.id">
            <div>{{instructValue.no}}   <b>{{instructValue.head}}</b> {{instructValue.content}}</div>
        </div>
    </div>
</template>