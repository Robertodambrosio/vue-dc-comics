<template>
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
                <img src="../../../assets/img/dc-logo-bg.png" alt="logo-footer">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterMain'
    }
</script>

<style lang="scss" scoped>
    .footer-main-bg {
        background-image: url("../../../assets/img/footer-bg.jpg");
        height: 70%;
        background-size: cover;

        .container {
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;

            .list-container {
                display: flex;

                ul {
                    margin-left: 30px;
                    list-style: none;

                    h3 {
                        color: white;
                        font-size: 20px;
                    }

                    li {
                        line-height: 20px;

                        a {
                            text-decoration: none;
                            color: grey;
                            font-size: 12px;
                            font-weight: italic;

                        }

                    }
                }
            }

            .footer-logo img {
                position: relative;
                z-index: 0;
            }
        }
    }
</style>