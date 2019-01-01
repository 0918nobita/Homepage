<template>
  <div>
    <vue-mathjax :formula="formula"></vue-mathjax>
  </div>
</template>

<script>
import { VueMathjax } from 'vue-mathjax'

export default {
  components: {
    'vue-mathjax': VueMathjax
  },
  name: 'Index',
  data () {
    return {
      formula: '$$ F = ma $$'
    }
  }
}
</script>

<style scoped>
</style>
