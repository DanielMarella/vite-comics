<template>
    <main>
        <div class="content-container">
            <div class="content">
                <MainCard v-for="card in products" 
                :cardElement = "card" />
            </div>
            <div class="main-card">

            </div>
        </div>
    </main>
</template>

<script>
import MainCard from './MainCard.vue';
export default {
    name : 'MainApp',

    components : {
        MainCard
    },

    data() {
        return {
            products : [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book",
                },
                
            ]
        }
    },




}
</script>

<style lang="scss">

    main{
        background-color: #202020;
        color: white;
    }

    .content{
        margin: 0 150px;
    }

    .main-card{
        background-color: #467df5;
        height: 150px;
        width: 100%;
    }
</style>