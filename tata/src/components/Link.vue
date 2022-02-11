<template>
  <div>
    <a :href="link" target="_blank"> By Let </a>
  </div>
</template>

<script>
export default {
  name: 'Link',
  props: {
      link: String
  }
}
</script>

<style scoped>

a {
    color: #FDBCD9;
    font-size: 15px;
}

</style>
