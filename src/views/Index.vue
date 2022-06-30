<template>
  <div>
    <Slider/>
    <div class="px-20">
      <MetodosPago/>
      <SliderProductos :title="'Basado en tu ultima visita'"/>
      <SliderProductos :title="'Ofertas'"/>
      <Level6/>
    </div>
  </div>
</template>

<script>
import Slider from '@/components/Slider.vue'
import MetodosPago from '@/components/MetodosPago.vue'
import SliderProductos from '@/components/SliderProductos.vue'
import Level6 from '@/components/Level6.vue'

export default {
  name: 'Home',
  components: {
    Slider,
    MetodosPago,
    SliderProductos,
    Level6
  }
}
</script>

<style scoped>
  
</style>