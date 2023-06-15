<template>
    <main>
        <div class="content-container">
            <div class="content">
                <h1>
                    &RightArrow;  Content Container &LeftArrow; 
                </h1>
            </div>
            <div class="main-card">

            </div>
        </div>
    </main>
</template>

<script>
export default {
    name : 'MainApp',
}
</script>

<style lang="scss">

    main{
        background-color: #202020;
        color: white;
        height: calc(70vh - 150px - 100px - 150px);
    }
    .content-container{
        height: 150px;
    }
    
    .content{
        height: 120px;
        margin: 0 150px;
        display: flex;
        align-items: center;
    }


    .main-card{
        background-color: #467df5;
        height: 150px;
        width: 100%;
    }
</style>