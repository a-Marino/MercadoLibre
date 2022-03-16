<template>
  <div>
    <Slider/>
    <div class="px-20">
      <MetodosPago/>
    </div>
  </div>
</template>

<script>
import Slider from '@/components/Slider.vue'
import MetodosPago from '@/components/MetodosPago.vue'

export default {
  name: 'Home',
  components: {
    Slider,
    MetodosPago
  }
}
</script>

<style scoped>
  
</style>