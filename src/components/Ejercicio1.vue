<template>
  <div>
    <input v-model="nombre" type="text">
    <p>Hola {{nombre}}!!</p>
  </div>
</template>

<script>
export default {
  name: 'Ejercicio1',
  data: function(){
    return {
      nombre: ""
      // put your variables here...
    }
  },
  methods: {
    // put your methods here...
  }
}
</script>

<style>

</style>