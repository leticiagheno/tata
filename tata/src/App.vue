<template>
  <div>
    <div v-if="dentroHorarioTrabalho">
      <app-titulo texto="Faltam" cor="verde" tamanho="big"/>
      <app-relogio />
      <app-titulo texto="para a tata sair do trabalho!" cor="verde"  tamanho="normal"/>
    </div>
    <div v-else> 
        <app-titulo texto="Fora do horário de trabalho!" cor="verde" tamanho="big"/>
    </div>
    
    <app-link class="padding-footer" link="https://github.com/leticiagheno"/>
  </div>
</template>

<script>
import AppTitulo from './components/Titulo.vue';
import AppRelogio from './components/Relogio.vue';
import AppLink from './components/Link.vue';

export default {
  name: 'App',
  components: {
    AppTitulo,
    AppRelogio,
    AppLink
  },
  data() {
    return {
      dentroHorarioTrabalho: true
    }
  }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css?family=Chelsea+Market');

body {
  font-family: 'Chelsea Market';
  min-height: 100vh;
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

.padding-footer {
  padding-top: 40px;
  text-align: center;
}

</style>
