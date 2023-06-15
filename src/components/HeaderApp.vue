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
    }

    .header-container{
        width: 100%;
        height: 10vh;
        margin-top: 30px;
        background-color: #fff;
        display: flex;
        align-items: center;
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