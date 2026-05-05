<template>
  <div>
  <h1>Olá mundo!</h1>
  <PrimeiroComponente />
  <p>O dado de app é: {{ testando }}</p>
  </div>
</template>

<script>

import PrimeiroComponente from './components/PrimeiroComponente.vue'

  export default{
    name: 'App',
    components: {
      PrimeiroComponente,
    },

    data(){
      return{
        testando: "Teste"
      }
    }
  }
</script>
