<template>
<footer>
    <div class="sign-up-now">
    <button>SIGN UP NOW !!</button>
    </div>

    <div class="social">
          <h2>Follow us</h2>
          <img src="../assets/img/footer-facebook.png" alt="facebook">
          <img src="../assets/img/footer-twitter.png" alt="facebook">
          <img src="../assets/img/footer-youtube.png" alt="facebook">
          <img src="../assets/img/footer-pinterest.png" alt="facebook">
          <img src="../assets/img/footer-periscope.png" alt="facebook">
    </div>
</footer>   
</template>

<script>
export default {
    name: 'AppFooter',
    
}
</script>

<style scoped lang="scss">

footer{
 background-color: #303030;
 display: flex;
 justify-content: space-around;
 align-items: center;
 padding: 40px;
 height: 60px;
}

h2{
 color: white;
 color: #0282f9;
}

button{
 padding: 10px;
 background: none;
 border: 1px solid #0282f9;
 color: white;
}

.social{
   display: flex;
   align-items: center;

           h2, img {
               margin-right: 20px;
            }
            img{
                width: 30px;
            }
}

</style>