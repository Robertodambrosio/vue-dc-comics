<template>
  <div class="footer-top-bg">
    <div class="container">
      <div class="option-container">
        <div class="option" v-for="(opt, i) in option" :key="i">
          <img :src="opt.src" :alt="opt.alt" />
          <span>{{opt.name}}</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'FooterTop',
    data() {
      return {
        option: [{
          src: '../../../assets/img/buy-comics-digital-comics.png',
          alt: 'DC',
          name: 'Digital Comics'
        },
        {
          src: '../../../assets/img/buy-comics-merchandise.png',
          alt: 'Merch',
          name: 'DC Merchandise'
        },
        {
          src: '../../../assets/img/buy-comics-subscriptions.png',
          alt: 'Sub',
          name: 'Subscriptions'
        },
        {
          src: '../../../assets/img/buy-comics-shop-locator.png',
          alt: 'CSL',
          name: 'Comic shop locator'
        },
        {
          src: '../../../assets/img/buy-dc-power-visa.svg',
          alt: 'Visa',
          name: 'Dc Power Visa'
        },
        ]
      }
    }
  };
</script>

<style lang="scss" scoped>
  .footer-top-bg {
    background-color: #0282f9;
    height: 15%;
    position: relative;
    z-index: 1;

    .container {
      height: 100%;

      .option-container {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-around;

        .option {
          display: flex;
          align-items: center;

          img {
            width: 35px;
            margin-right: 10px;
          }

          span {
            color: white;
            text-transform: uppercase;
            font-size: 12px;
          }
        }
      }
    }
  }
</style>