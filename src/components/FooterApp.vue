<template>
    <footer>
        <div class="footer-link">
            <div class="dc-comics">
                <h3>DC COMICS</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>news</li>
                </ul>
                <div class="shop">
                    <h3>SHOP</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
            </div>
            <div class="dc">
                <h3>DC</h3>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (new)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshop</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contacts Us</li>
                </ul>
            </div>
            <div class="sites">
                <h3>SITES</h3>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Vista</li>
                </ul>
            </div>
        </div>
        <div class="end-footer">
            <div class="sign-up">
                <button>SIGN-UP-NOW</button>
            </div>
            <div class="social">
                <ul>
                    <li><a href="#"></a>link</li>
                    <li><a href="#"></a>link</li>
                    <li><a href="#"></a>link</li>
                    <li><a href="#"></a>link</li>
                    <li><a href="#"></a>link</li>
                    <li><a href="#"></a>link</li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name : 'FooterApp',
}
</script>

<style lang="scss">
    footer{
        color: white;
        height: calc(95vh - 2px - 150px - 100px - 150px);
        background-image: url(../assets/img/footer-bg.jpg);
    }

    .footer-link {
        width: 450px;
        height: 45vh;
        display: flex;
        flex-wrap: wrap;
        padding-top: 40px;
        margin-left: 150px;
    }

    h3{
        margin: 10px 10px;

    }

    ul{
        margin: 0 10px;
    }

    li{
        color: grey;
        margin: 5px 0;
        font-size: .9rem;
    }

    .shop{
        margin-top: 25px;
    }

    .end-footer{
        display: flex;
        justify-content: space-between;
        background-color: #303030;
        height: 10vh;

            ul{
                display: flex;

                li{
                    margin: 0 10px;

                }
            }
        }

</style>