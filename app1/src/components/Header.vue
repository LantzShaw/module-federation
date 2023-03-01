<template>
  <div>
    <h1>Page Header {{ name }}</h1>
    <h2>Header</h2>
    <Test />
  </div>
</template>
<script>
import Test from './Test.vue'
export default {
  props: {
    name: {
      type: String,
      default: '',
    },
  },
  components: { Test },
}
</script>
<style></style>
