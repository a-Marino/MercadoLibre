<template>
  <div id="app">
    <Nav/>
    <router-view/>
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'

export default {
  name: "App",
  components: {
    Nav,
  }
}
</script>

<style>
  :root {
    --amarillo-meli: #FFF159;
  }

 * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    overflow-x: hidden;
 }

 body {
    height: 100%;
    width: 100%;
    background-color: #EBEBEB;
 }
</style>
