<template>
  <div id="app">
    <titulo texto="Faltam" cor="verde" tamanho="big"/>
    <titulo texto="10h:50" cor="rosa"/>
    <titulo texto="para a tata sair do trabalho" cor="verde"  tamanho="normal"/>
    <titulo texto="By Let" cor="rosa" tamanho="tiny"/>
  </div>
</template>

<script>
import Titulo from './components/Titulo.vue';

export default {
  name: 'App',
  components: {
    Titulo
  }
}
</script>
]
<style>
</style>
