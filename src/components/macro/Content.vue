<template>
  <main>
      <Hero/>
      <div class="container">
          <h2>CURRENT SERIES</h2>
          <Comics/>
          <button class="btn-content">Load more</button>
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
main {
    background-color: #1c1c1c;
    color: white;
    text-align: center;
    position: relative;

    h2 {
        position: absolute;
        top: 29%;
        left: 10%;
        font-size: 20px;
        background: #0282f9;
        padding: 10px 30px;
    }

    .btn-content {
        padding: 8px 40px;
        border: none;
        color: white;
        background: #0282f9;
        margin-bottom: 40px;
        text-transform: uppercase;
        font-weight: bold;
    }
}


</style>