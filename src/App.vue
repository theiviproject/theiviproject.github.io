<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import AppNav from "@/components/AppNav.vue";
</script>

<template>
  <header class="v-app__header">
    <img alt="ivi logo"
         class="v-app__header__logo"
         src="@/assets/logo.svg" />

    <app-nav></app-nav>

  </header>

  <RouterView />


</template>

<style lang="scss">

#app {
  min-height: 100vh;
  padding-top: var(--nav-height);
}


.v-app__header {
  display: flex;
  align-items: center;
  padding: var(--gutter-half);
  justify-content: space-between;
  height: var(--nav-height);
  background-color: var(--color-background);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
  box-shadow: 0 0 30px 30px var(--color-background);
}
.v-app__header__logo {
  display: block;
  height: 100%;
  box-sizing: border-box;
  padding: var(--gutter-half);
  width: auto;
}

</style>
