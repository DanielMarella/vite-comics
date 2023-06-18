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
        <div class="footer-logo">

        </div>
        <div class="end-footer">
            <div class="background">

                <div class="sign-up">
                    <button>SIGN-UP NOW!</button>
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
        </div>
    </footer>
</template>

<script>
export default {
    name : 'FooterApp',
}
</script>

<style lang="scss" scoped>
    footer{
        color: white;
        position: relative;
        background-color: #303030;
        background-image: url(../assets/img/footer-bg.jpg);
    }
    
    
    
    .footer-link {
        width: 1200px;
        height: 45vh;
        display: flex;
        flex-wrap: wrap;
        padding-top: 40px;
        margin: 0 auto;
    }

    .footer-logo{
        position: absolute;
        background-image: url(../assets/img/dc-logo-bg.png);
        width: 600px;
        height: 495px;
        background-repeat: no-repeat;
        top: -60px;
        left: 50%;

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
        background-color: #303030;
        button{
            font-size: 1.2rem;
            color: white;
            padding: 20px 50px;
            border: 3px solid #467df5;
            background-color: #303030;
            
        }
        
        ul{
            display: flex;
            li{
                margin: 0 10px;
                    color: white;
                    text-decoration: none;
                }
            }
            .background{
                width: 100%;
                display: flex;
                justify-content: space-between;
                align-items: center;
                width: 1200px;
                margin: 0 auto;
                padding: 30px 0;
            }
        }
        
</style>