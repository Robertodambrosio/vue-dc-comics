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

</style>