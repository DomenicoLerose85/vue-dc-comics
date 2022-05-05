<template>
  <div id="app">
  <header>
   <app-header/>
  </header>

  <main>
   <MyJumbotron/>
   <app-grid/>
  </main>

  <footer>
   <middle-footer/>
   <app-footer/>
  </footer>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppGrid from './components/AppGrid.vue'
import MiddleFooter from './components/MiddleFooter.vue'
import AppFooter from './components/AppFooter.vue'
import MyJumbotron from './components/MyJumbotron.vue'


export default {
  name: "App",
  components: {
    AppHeader,
    MyJumbotron,
    AppGrid,
    MiddleFooter,
    AppFooter,
  },
  data(){
    return {
      listaHeader: ["Characters", "Comics", "Movies", "Tv", "Games", "Collectibles", "Videos", "Fans", "News", "Shop"],

      footerLists: {
        list1: ["Characters", "Comics", "Movies", "Tv", "Games", "Videos", "News"],
        list2: ["Shop DC", "Shop DC Collectibles"],
        list3: ["Terms of use", "Privacy policy (New)","Ad Choices","Advertising","Jobs","Subscriptions","Talent workshops","CPSC certificates","Ratings","Shop helps","contact us"],
        list4: ["DC", "Mad Magazine", "DC Kids", "DC Universe", "DC Power visa"]
      }
    }
  }
};
</script>


<style lang='scss'>
@import './style/variables';
@import './style/general';




</style>
