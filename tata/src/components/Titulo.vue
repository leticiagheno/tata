<template>
  <div>
    <p :class="`${cor} ${tamanho}`"> {{ texto }} </p>
  </div>
</template>

<script>
export default {
  name: 'Titulo',
  props: {
    texto: String,
    cor: String,
    tamanho: String
  }
}
</script>

<style scoped>
.verde {
    color: #a8e077;
}

.rosa {
    color: #FDBCD9;
}

.tiny {
    font-size: 30px;
}

.normal {
    font-size: 75px;
}

.big {
    font-size: 150px;
}

</style>
