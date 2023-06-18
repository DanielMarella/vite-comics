<template>
    <div class="jumbo">
        <img :src="getImagePath(jumboImg)" alt="">
    </div>
    <div class="current-series">
        <p>current series</p>
    </div>
</template>

<script>
export default {
    name : 'JumboTron',    
    data() {
        return {
            jumboImg : "jumbotron.jpg",


        }
    },
    
                methods : { 
                    getImagePath : function(img) {
                    return new URL (`../assets/img/${img}`, import.meta.url).href;
                    }
                }
}

</script>

<style lang="scss" scoped>
    .jumbo{
        position: relative;
        width: 100%;
        height: 400px;
        
            img{
                width: 100%;
                height: 100%;
                object-fit: cover;
                object-position: top;
            }

        }
    .current-series{

        p{ 
            padding: 20px 50px;
            position: absolute;
            top: 500px;
            left: 350px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-transform: uppercase;
            background-color: #467df5;
        }
    }        
</style>