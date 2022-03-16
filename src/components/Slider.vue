<template>
    <div class="slider shadow-inner">
        <!-- Controles -->
        <div class="controles">
            <span class="arrow arrow-left shadow-inner cursor-pointer">&lt;</span>
            <span class="arrow arrow-right shadow-inner cursor-pointer">&gt;</span>
        </div>
        <img src="@/assets/slider/slider-1.jpg" alt="slider-1">
    </div>
</template>

<script>
export default {
    name: 'Slider'
}
</script>

<style scoped>
    .slider {
        position: relative;
        height: 340px;
        overflow: hidden;
    }

    .slider img {
        height: 340px;
        min-width: 1600px;
    }

    .slider:hover .controles {
        display: block;
    }

    .controles {
        position: absolute;
        width: 100vw;
        display: none;
        height: 100%;
        
    }

    .controles .arrow {
        font-size: 2rem;
        color: #3483fa;
        padding: 10px;
        background-color: white;
        position: relative;
        top: 140px;
    }

    .controles .arrow-left {
        border-radius: 0px 70px 70px 0px;
        margin-left: -10px;
    }

    .controles .arrow-right {
        position: absolute;
        border-radius: 70px 0px 0px 70px;
        right: 0;
        margin-right: -10px;
    }
</style>