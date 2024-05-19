<script setup>
import nutritionValues from "@/data/nutritionValues.json";
</script>

<style scoped>
.nutrient-main-ctn{
    padding:30px 0;
    
}
.nutrient-text{
    padding:10px 0;
}
.nutrient-list-container{

}
.nutrient-list{
    display:flex;
    line-height:4;
}
.nutrient{
    width:50%;
}
.amount{
    width:50%;
}
</style>

<template>
    <div class="nutrient-main-ctn">
        <h2>Nutrition</h2>
        <p class="nutrient-text">The table below shows nutritional values per serving without the additional fillings</p>
        <div 
            v-for="nutritionValue in nutritionValues"
            :key="nutritionValue.id"
            class="nutrient-list-container">
            <div class="nutrient-list">
                <div class="nutrient">
                    <p>{{nutritionValue.value}}</p>
                </div>
                <div class="amount">
                    <p>{{nutritionValue.amount}}</p>
                </div>
            </div>
            <hr/>
        </div>
        
    </div>
</template>