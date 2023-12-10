<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
export default {
  components: { AppHeader, AppFooter, AppMain },
}
</script>

<template>
  <div class="container">
    <header>
      <app-header />
    </header>
    <main>
      <app-main />
    </main>
    <footer>
      <app-footer />
    </footer>
  </div>
</template>

<style lang="scss">
@use './assets/styles/general.scss' as *;
</style>