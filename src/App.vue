<template>
  <div id="app">
  <header>
   <app-header/>
  </header>

  <main>
   <app-grid/>
  </main>

  <footer>
   <app-footer/>
  </footer>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppGrid from './components/AppGrid.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  name: "App",
  components: {
    AppHeader,
    AppGrid,
    AppFooter,
  },
};
</script>


<style lang='scss'>
@import './style/variables';
@import './style/general';




</style>
