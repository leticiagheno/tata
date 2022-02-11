<template>
  <div>
    <span :class="`${cor} ${tamanho}`"> {{ texto }} </span>
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

.normal {
    font-size: 50px;
}

.big {
    font-size: 75px;
}
</style>
