<style scoped>
.main-hero-image-ctn{
    width:100%;
    height:100%;
}
.main-hero-image-ctn img{
    width:100%;
    height:100%;
}
.main-hero-text-section h1{
    font-weight:400;
    font-size:30px;
    font-family: "Young Serif", serif;
    font-style: normal;
}
.hero-title-text{
    color: hsl(30, 10%, 34%);
    font-size: 16px;
    font-family: "Outfit", sans-serif;
    line-height:2;
    text-align:justify;
}
.prep-time{
    background-color: hsl(330, 100%, 98%);
    font-family: "Outfit", sans-serif;
    padding:30px 50px;
    line-height:3;
}
.prep-time h2{
    color:hsl(332, 51%, 32%);
    font-weight:600;
}
.prep-time ul{
    color: hsl(30, 10%, 34%);
}
</style>

<template>
    <div class="main-hero">
        <div class="main-hero-image-ctn">
            <img src="/public/image-omelette.jpeg" alt="Hero Omelette image">
        </div><br/>
        <div class="main-hero-text-section"><br>
            <h1>Simple Omelette Recipe</h1><br>
            <p class="hero-title-text">
                An easy and quick dish, perfect for any meal. This classic omelette combines
                beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats
            </p><br><br>
            <div class="prep-time">
                <h2>Preparation time</h2>
                <ul>
                    <li><b>Total</b>: Approximately 10 minutes</li>
                    <li><b>Preparation</b>: 5 minutes</li>
                    <li><b>Cooking</b>: 5 minutes</li>
                </ul>
            </div>
        </div>
    </div>
</template>