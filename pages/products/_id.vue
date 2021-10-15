<template>
  <div>
    Products
    {{products}}
  </div>
</template>

<script>
  import {mapState} from "vuex"

  export default {
    computed: {
    ...mapState(['products'])
    }
  }
</script>

<style  scoped>

</style>
