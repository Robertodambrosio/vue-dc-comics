<template>
    <footer>
        <div class="footer-top-bg">
            <div class="container">
                <div class="option-container">
                    <div class="option">
                        <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                        <span>Digital Comics</span>
                    </div>
                    <div class="option">
                        <img src="../assets/buy-comics-merchandise.png" alt="merch">
                        <span>Dc merchandise</span>
                    </div>
                    <div class="option">
                        <img src="../assets/buy-comics-subscriptions.png" alt="sub">
                        <span>Subscriptions</span>
                    </div>
                    <div class="option">
                        <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
                        <span>Comic shop locator</span>
                    </div>
                    <div class="option">
                        <img src="../assets/buy-dc-power-visa.svg" alt="visa-power">
                        <span>Dc</span>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-main-bg">
            <div class="container">
                <div class="footer-menu-sx">
                    <div class="list-container">
                        <ul>
                            <h3>Title</h3>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                        </ul>
                        <ul>
                            <h3>Title</h3>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                        </ul>
                        <ul>
                            <h3>Title</h3>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                        </ul>
                        <ul>
                            <h3>Title</h3>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>
                            <li><a href="">Test</a></li>

                        </ul>
                    </div>
                </div>
                <div class="footer-logo">
                    <img src="../assets/dc-logo-bg.png" alt="logo-footer">
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <div class="footer-bottom-sx">
                    <button class="btn"><span>Sign-up now!</span></button>
                </div>
                <div class="footer-bottom-dx">

                </div>
            </div>
        </div>
        <div class="footer-very-bottom"></div>


    </footer>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style lang="scss" scoped>
    footer {
        height: 90vh;

        .footer-top-bg {
            background-color: #0282f9;
            height: 20%;
            position: relative;
            z-index: 1;

            .container {
                height: 100%;


                .option-container {
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: space-around;

                    .option {
                        display: flex;
                        align-items: center;

                        img {
                            width: 40px;
                            margin-right: 10px;
                        }

                        span {
                            color: white;
                            text-transform: uppercase;
                            font-size: 12px;
                        }
                    }
                }
            }
        }

        .footer-main-bg {
            background-image: url("../assets/footer-bg.jpg");
            height: 60%;
            background-size: cover;

            .container {
                height: 100%;
                display: flex;
                justify-content: space-between;
                align-items: center;

                .list-container {
                    display: flex;

                    ul{
                        margin-left: 30px;
                        list-style: none;

                        h3{
                            color: white;
                            font-size: 20px;
                        }

                        li {
                            line-height: 20px;
                        
                        a{
                            text-decoration: none;
                            color: grey;
                            font-size: 12px;
                            font-weight: italic;

                        }   
                        
                        }
                    }
                }

                .footer-logo img{
                    position:relative;
                    z-index: 0;
                }
            }
        }
        .footer-bottom {
            background-color: #303030;
            height: 15%;
            position: relative;
            z-index: 1;
        }
        .footer-very-bottom {
            background: rgb(0, 1, 37);
            height: 5%;
        }

    }
</style>