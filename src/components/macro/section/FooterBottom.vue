<template>
    <div class="footer-bottom">
        <div class="container">
            <div class="footer-bottom-sx">
                <button class="btn"><span>Sign-up now!</span></button>
            </div>
            <div class="footer-bottom-dx">
                <img src="../../../assets/img/footer-facebook.png">
                <img src="../../../assets/img/footer-periscope.png">
                <img src="../../../assets/img/footer-pinterest.png">
                <img src="../../../assets/img/footer-twitter.png">
                <img src="../../../assets/img/footer-youtube.png">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterBottom'
    }
</script>

<style lang="scss" scoped>
    .footer-bottom {
        background-color: #303030;
        height: 15%;
        position: relative;
        z-index: 1;

        .container {
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;

            button {
                border: 2px solid #0282f9;
                background-color: transparent;
                color: white;
                text-transform: uppercase;
                padding: 10px 20px;
            }

            .footer-bottom-dx img{
                margin-left: 10px;
            }
        }
    }
</style>