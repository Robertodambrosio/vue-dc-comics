<template>
    <footer>
        <div class="container">
            <div class="footer-top">
                <div class="option">
                    <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                    <span>Testo</span>
                </div>
                <div class="option">
                    <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                    <span>Testo</span>
                </div>
                <div class="option">
                    <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                    <span>Testo</span>
                </div>
                <div class="option">
                    <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                    <span>Testo</span>
                </div>
                <div class="option">
                    <img src="../assets/buy-comics-digital-comics.png" alt="dc-sp">
                    <span>Testo</span>
                </div>
            </div>
            <div class="footer-main">

            </div>
            <div class="footer-bottom">

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
    footer {
        background-color: #0282f9;
        height: 100px;

        .container {
            height: 100%;

            .footer-top {
                height: 100%;
                display: flex;
                justify-content: space-around;

                .option {
                    display: flex;
                    align-items: center;

                    img {
                        width: 40px;
                    }
                }


            }
        }
    }
</style>