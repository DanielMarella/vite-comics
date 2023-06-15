<template>
    <header>
        <div class="header-container">
            <div class="head-logo">
                <ul>
                    <li>Logo</li>
                </ul>
            </div>
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
}
</script>
<style lang="scss">

    header{
        position: relative;
        background-color: #202020;
        height: 150px;
    }

    .header-container{
        width: 100%;
        padding: 3rem 0;
        position: relative;
        top: 30%;
        background-color: #fff;
        display: flex;
        justify-content: space-between;
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