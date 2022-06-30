<template>
    <div class="flex flex-col mb-5 rounded-t-md">
        <div class="gradient w-full flex flex-row justify-between p-5 items-center">
            <div>
                <span class="text-2xl text-white font-semibold">Subscribite al nivel 6</span>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col text-white -space-y-2 border-l-2 pl-1">
                    <span class="line-through text-sm">$ 1.199</span>
                    <span class="text-2xl font-semibold">$ 399 <span class="text-base">/mes</span></span>
                </div>
                <span class="bg-verde text-xs text-white rounded-full p-1">67% OFF TODO UN AÑO</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Level 6'
    }
</script>

<style scoped>
    .gradient {
        background: -webkit-gradient(linear,left top,right top,color-stop(55%,#a90f90),to(#0c1a51));
    }
</style>