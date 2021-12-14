<template>
  <div class="footer-top-bg">
    <div class="container">
      <div class="option-container">
        <div class="option">
          <img src="../../../assets/img/buy-comics-digital-comics.png" alt="dc-sp" />
          <span>Digital Comics</span>
        </div>
        <div class="option">
          <img src="../../../assets/img/buy-comics-digital-comics.png" alt="merch" />
          <span>Dc merchandise</span>
        </div>
        <div class="option">
          <img src="../../../assets/img/buy-comics-digital-comics.png" alt="sub" />
          <span>Subscriptions</span>
        </div>
        <div class="option">
          <img src="../../../assets/img/buy-comics-digital-comics.png" alt="shop-locator" />
          <span>Comic shop locator</span>
        </div>
        <div class="option">
          <img src="../../../assets/img/buy-comics-digital-comics.png" alt="visa-power" />
          <span>Dc</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'FooterTop',
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