<template>
  <div>
    <Slider/>
    <div class="px-20">
      <MetodosPago/>
      <SliderProductos :title="'Basado en tu ultima visita'"/>
      <SliderProductos :title="'Ofertas'"/>
    </div>
  </div>
</template>

<script>
import Slider from '@/components/Slider.vue'
import MetodosPago from '@/components/MetodosPago.vue'
import SliderProductos from '@/components/SliderProductos.vue'

export default {
  name: 'Home',
  components: {
    Slider,
    MetodosPago,
    SliderProductos
  }
}
</script>

<style scoped>
  
</style>