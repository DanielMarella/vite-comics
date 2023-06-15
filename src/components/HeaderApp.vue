<template>
    <header>
        <div class="header-container">
            <div class="head-logo">
            </div>
            <img :src="getImagePath(`../assets/img/${imageLogo}`)" alt="">
            <div class="head-nav">
                <ul>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name : 'HeaderApp',
    data(){
        return{
            imageLogo : "dc-logo.png"
        }

        
    },
    methods : { 
        getImagePath : function(imgPath) {
        return new URL (imgPath, import.meta.url).href;
        }
    }


}
</script>
<style lang="scss">

    .header-container{
        width: 100%;
        height: 10vh;
        margin-top: 30px;
        background-color: #fff;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    img{
        width: 80px;
    }

    .head-nav{
            ul{
                display: flex;
            }

            li{
                margin: 0 10px;
            }
        }




</style>