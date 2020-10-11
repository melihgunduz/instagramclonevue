<template>
  <div class="container">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'Container',
  components: {}
}
</script>

<style scoped>
.container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
</style>
