<template>
  <div id="app">
    <counter></counter>
    <counter></counter>
  </div>
</template>

<script>
import counter from './components/counter.vue'

export default {
  name: 'app',
  components: { counter }
}
</script>

