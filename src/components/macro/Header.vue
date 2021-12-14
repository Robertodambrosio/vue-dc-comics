<template>
    <div class="container header">
        <div class="logo">
            <img src="../../assets/img/dc-logo.png" alt="dc-logo">
        </div>
        <nav>
            <ul>
                <li v-for="(link, i) in links" :key="i" :class="{active : link.visible}">
                    <a :href="link.url">{{ link.text }}</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
    export default {
        name: 'Header',
        data() {
            return {
                links: [{
                        text: "CHARACTERS",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "COMICS",
                        url: "#",
                        visible: true,
                    },
                    {
                        text: "MOVIES",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "TV",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "GAMES",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "COLLECTIBLES",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "VIDEOS",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "FANS",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "NEWS",
                        url: "#",
                        visible: false,
                    },
                    {
                        text: "SHOP",
                        url: "#",
                        visible: false,
                    },
                ],
            };
        },
    }
</script>

<style lang="scss" scoped>
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 10vh;

        img {
            width: 60px;
        }

        ul {
            display: flex;
            justify-content: space-around;
            list-style: none;

            li {
                padding: 20px;

                .active {
                    color:blue
                }

                a {
                    text-decoration: none;
                    text-transform: uppercase;
                    font-size: 14px;
                    font-weight: 600;
                }
            }
        }
    }
</style>