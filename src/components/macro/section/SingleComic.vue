<template>
    <div class="comic">
        <img :src="comic.thumb" :alt="comic.type">
        <p>{{comic.series}}</p>
    </div>
</template>

<script>
    export default {
        name: 'SingleComic',
        props : {
            comic: Object
        }
    }
</script>

<style lang="scss" scoped>
    .comic {
        margin-top: 40px;
        width: 200px;

        p {
            text-align: left;
            padding-top:  10px;
            text-transform: uppercase;
            font-size: 13px;
        }
    }
</style>