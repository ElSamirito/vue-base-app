<template>
  <div>
    <input v-model.number="num1" type="text">
    <input v-model.number="num2" type="text">
    <p>{{resultado(num1, num2)}}</p>
  </div>
</template>

<script>
export default {
  name: 'Ejercicio2',
  data: function(){
    
    return {
      // put your variables here...
      num1: 1,
      num2: 1,
    }
  },
  methods: {
    resultado(a, b){
      return a+b
    }
    // put your methods here...
  }
}
</script>

<style>

</style>