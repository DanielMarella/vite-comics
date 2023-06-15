<template>
    <header>
        <div class="header-container">
            <div class="head-logo">
                <img :src="getImagePath(`../assets/img/${imageLogo}`)" alt="">
            </div>
            <div class="head-nav">
                <ul>
                    <li v-for="link in linkHeader" :class=" link.active ? 'active' : ''">
                        <a :href="link.link" >
                            {{ link.name }}
                        </a>
                        
                    </li>
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
            imageLogo : "dc-logo.png",

            linkHeader : [
                {
                    link : '#',
                    name: 'characters',
                    active : false
                },
                {
                    link : '#',
                    name: 'comics',
                    active : true
                },
                {
                    link : '#',
                    name: 'movies',
                    active : false
                },
                {
                    link : '#',
                    name: 'tv',
                    active : false
                },
                {
                    link : '#',
                    name: 'games',
                    active : false
                },
                {
                    link : '#',
                    name: 'collectibles',
                    active : false
                },
                {
                    link : '#',
                    name: 'videos',
                    active : false
                },
                {
                    link : '#',
                    name: 'fans',
                    active : false
                },
                {
                    link : '#',
                    name: 'news',
                    active : false
                },
                {
                    link : '#',
                    name: 'shop',
                    active : false
                },
                
            ]

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
        height: 10vh;
        margin-top: 30px;
        background-color: #fff;
        display: flex;
        justify-content: space-between;
    }


    img{
        width: 80px;
    }

    .head-logo{
        display: flex;
        align-items: center;
        margin-left: 150px;
    }

    .head-nav{
        margin-right: 150px;
    }


    .head-nav{
            ul{
                display: flex;
                align-items: center;
                height: 100%;
                text-transform: uppercase;
            }

            li{
                display: flex;
                align-items: center;
                height: 100%;
                margin: 0 10px;
            }
        }


</style>