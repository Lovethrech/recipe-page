<script setup>
import instructValues from "@/data/instructValues.json";
</script>

<style scoped>
.instruction-main-ctn{
    padding:30px 0;
    line-height:3;
}
.instruction-main-ctn ol{
    padding:0 30px;
}
</style>

<template>
    <div class="instruction-main-ctn">
        <h2>Instructions</h2>
        <ol v-for="instructValue in instructValues" :key="instructValue.id">
            <li><b>{{instructValue.head}}</b>{{instructValue.content}}</li>
        </ol>
    </div>
</template>