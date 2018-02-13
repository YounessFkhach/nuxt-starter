<template>
  <h1>Hi num {{ id }}</h1>
</template>

<script>
export default {
  computed: {
    id() {
      return this.$route.params.id
    }
  }
}
</script>

<style>

</style>
