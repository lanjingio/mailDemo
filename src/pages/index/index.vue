<template>
  <div class="demo">
    {{demo}}
  </div>
</template>

<script>
  export default {
    data () {
      return {
        demo: 'index'
      }
    }
  }
</script>

<style lang="less" scoped>
  .demo {
    color: red;
  }
</style>
