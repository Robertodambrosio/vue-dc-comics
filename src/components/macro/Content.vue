<template>
  <main>
      <Hero/>
      <div class="container">
          <Comics/>
      </div>    
  </main>
</template>

<script>
import Hero from '../macro/section/Hero.vue'
import Comics from '../macro/section/Comics.vue'



export default {
name: 'Content',
components: {
    Hero,
    Comics
}
}
</script>

<style lang="scss" scoped>



</style>