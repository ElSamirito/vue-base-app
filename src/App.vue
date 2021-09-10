<template>
  <div id="app">
    <h1>Ejercicio N°1</h1>
    <Ejercicio1 />
    <h1>Ejercicio N°2</h1>
    <Ejercicio2 />
  </div>
</template>

<script>
import Ejercicio1 from "./components/Ejercicio1.vue"
import Ejercicio2 from "./components/Ejercicio2.vue"

export default {
  components: {
    Ejercicio1,
    Ejercicio2,
  },
  name: 'App',
}
</script>

<style>

</style>