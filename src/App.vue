<template>
  <div id="app">
    <MainNavigation />
    <router-view />
  </div>
</template>

<script>
import MainNavigation from '@/components/global/MainNavigation.vue'
export default {
  name: 'App',
  components: {
    MainNavigation
  }
}
</script>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }
  body {
    background: $blue;
  }
</style>
