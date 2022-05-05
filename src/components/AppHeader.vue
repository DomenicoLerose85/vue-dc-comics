<template>
<header>
  <img src="../assets/img/dc-logo.png" alt="Dc Logo">
  <nav>
    <ul>
      <li v-for="(item, index) in links" :key="index" :class="{'selected' : item.active}">{{item.testo}}</li>
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
          link: "#",
          active: false,
        },
        {
          testo: "COMICS",
          link: "#",
          active: true,
        },
        {
          testo: "MOVIES",
          link: "#",
          active: false,
        },
        {
          testo: "TV",
          link: "#",
          active: false,
        },
        {
          testo: "GAMES",
          link: "#",
          active: false,
        },
        {
          testo: "COLLETIBLES",
          link: "#",
          active: false,
        },
        {
          testo: "VIDEOS",
          link: "#",
          active: false,
        },
        {
          testo: "FANS",
          link: "#",
          active: false,
        },
        {
          testo: "NEWS",
          link: "#",
          active: false,
        },
        {
          testo: "SHOP",
          link: "#",
          active: false,
        },
      ]
    }
  }, 
  // props: 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss"  scoped>

header{
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 10px;
}

img {
  width: 50px;
  height: 50px;
  margin-right: 200px;
}

ul{
  display: flex;
}

li{
 padding: 10px;
 font-size: 10px;
 font-weight: bold;
 display: flex;
 align-items: center;
 border-bottom: 2px solid transparent;

    &:hover{
       color: #0282f9;
       border-bottom: 2px solid #0282f9;
       cursor: pointer;
    }   
}


</style>
