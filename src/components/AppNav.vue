<template>
  <nav class="app-nav">
    <RouterLink to="/#intro">introduction</RouterLink>
    <RouterLink to="/#resources">resources</RouterLink>
  </nav>
</template>

<script lang="ts" setup>



</script>

<style lang="scss" scoped>
.app-nav {
  display: flex;

  > * {
    padding: var(--gutter-half);
  }
}
</style>