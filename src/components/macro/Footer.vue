<template>
    <footer>
        <FooterTop/>
        <FooterMain/>
        <FooterBottom/>
    </footer>
</template>

<script>

import FooterTop from '../macro/section/FooterTop.vue';
import FooterMain from '../macro/section/FooterMain.vue';
import FooterBottom from '../macro/section/FooterBottom.vue';


    export default {
        name: 'Footer',
        components: {
            FooterTop,
            FooterMain,
            FooterBottom
        }


    }
</script>

<style lang="scss" scoped>
    footer {
        height: 80vh;
    }
</style>