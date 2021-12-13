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




    </footer>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style lang="scss" scoped>
    .footer-top-bg {
        background-color: #0282f9;
        height: 100px;

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
</style>