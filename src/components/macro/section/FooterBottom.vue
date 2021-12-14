<template>
    <div class="footer-bottom">
        <div class="container">
            <div class="footer-bottom-sx">
                <button class="btn"><span>Sign-up now!</span></button>
            </div>
            <div class="footer-bottom-dx">
                a
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
        }
    }
</style>