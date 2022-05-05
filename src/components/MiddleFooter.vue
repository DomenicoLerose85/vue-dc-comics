<template>
     <div class="footer-list">
            <div class="first-section">
                <h2>DC comics</h2>

                <ul>
                    <li v-for="(list, index) in list1" :key="index">{{list}}</li>
                </ul>

                <h2>Shop</h2>

                <ul>
                    <li v-for="(list, index) in list2" :key="index">{{list}}</li>
                </ul>
            </div>

            <div class="second-section">
                <h2>DC</h2>

                <ul>
                    <li v-for="(list, index) in list3" :key="index">{{list}}</li>
                </ul>

            </div>

            <div class="third-section">
                <h2>Sites</h2>

                <ul>
                    <li v-for="(list, index) in list4" :key="index">{{list}}</li>
                </ul>
            </div>

            <img src="../assets/img/dc-logo-bg.png" alt="logo bg">    
       </div>


</template>

<script>
export default {
    name: 'MiddleFooter'
    
}
</script>

<style lang="scss" scoped>

.footer-list{
    background-image: url("../assets/img/footer-bg.jpg");
    display: flex;
    justify-content: center;
    padding: 30px;
    height: 400px;
    overflow: hidden;

        img{
            margin-left: 200px;
            height: 500px;
            margin-left: 200px;
            overflow: hidden;
            position: relative;
            bottom: 90px;
        }

        h2{
            color: white;
            margin-left: 10px;
        }

        ul{
            margin-right: 20px;
        }

        li{
            color: grey;
            list-style: none;
            margin: 10px;
        }
}

</style>