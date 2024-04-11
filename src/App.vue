<script>
// JS
import AppHeader from './components/AppHeader.vue';
import AppList from './components/AppList.vue';
import AppInfo from './components/AppInfo.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components: {
    AppHeader,
    AppList,
    AppInfo,
    AppFooter
  }
}
</script>

<template>
  <!-- HTML -->
  <AppHeader></AppHeader>
  <main>
    <AppList></AppList>
    <AppInfo></AppInfo>
  </main>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
/* CSS */ 
@use './style/generic';
</style>
