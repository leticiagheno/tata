<template>
  <div>
    <h1> {{ horario }} </h1>
  </div>
</template>

<script>
export default {
  name: 'Relogio',
  props: {
    horario: String
  }
}
</script>

<style scoped>
h1 {
  color: #FDBCD9;
}
</style>
