<template>
    <div class="comic">
        <img :src="element.thumb" :alt="element.type">
        <p>{{element.series}}</p>
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