<template>
    <div>
        <input v-bind:type="type">
    </div>

</template>

<script>
export default {
  name: 'Input',
  props: {
      type: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
