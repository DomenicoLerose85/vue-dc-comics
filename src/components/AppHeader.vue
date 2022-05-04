<template>
<header>
  <img src="../assets/img/dc-logo.png" alt="Dc Logo">
  <nav>
    <ul>
      <li v-for="(item, index) in links" :key="index">{{item.testo}}</li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </nav>
</header>
  
</template>

<script>
export default {
  name: 'AppHeader',
  data(){
    return{
      links: [
        {
          testo: "CHARACTERS",
          link: "",
          active: false,
        },
        {
          testo: "COMICS",
          link: "",
          active: true,
        },
        {
          testo: "MOVIES",
          link: "",
          active: false,
        },
        {
          testo: "TV",
          link: "",
          active: false,
        },
        {
          testo: "GAMES",
          link: "",
          active: false,
        },
        {
          testo: "COLLETIBLES",
          link: "",
          active: false,
        },
        {
          testo: "VIDEOS",
          link: "",
          active: false,
        },
        {
          testo: "FANS",
          link: "",
          active: false,
        },
        {
          testo: "NEWS",
          link: "",
          active: false,
        },
        {
          testo: "SHOP",
          link: "",
          active: false,
        },
      ]
    }
  } 
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
