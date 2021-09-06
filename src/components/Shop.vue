<template>
  <div>
    <section id="shop-section">
      <div class="container d-flex align-center space-between">
        <!-- card -->
        <div class="shop-card d-flex align-center">
          <img
            class="buy-image"
            src="../assets/img/buy-comics-digital-comics.png"
            alt=""
          />
          <p>DIGITAL COMICS</p>
        </div>
        <!-- end card -->
        <!-- card -->
        <div class="shop-card d-flex align-center">
          <img
            class="buy-image"
            src="../assets/img/buy-comics-merchandise.png"
            alt=""
          />
          <p>DC MERCHANDISE</p>
        </div>
        <!-- end card -->
        <!-- card -->
        <div class="shop-card d-flex align-center">
          <img
            class="buy-image"
            src="../assets/img/buy-comics-subscriptions.png"
            alt=""
          />
          <p>SUBSCRIPTION</p>
        </div>
        <!-- end card -->
        <!-- card -->
        <div class="shop-card d-flex align-center">
          <img
            class="buy-image"
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
          />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <!-- end card -->
        <!-- card -->
        <div class="shop-card d-flex align-center">
          <img
            class="buy-image"
            src="../assets/img/buy-dc-power-visa.svg"
            alt=""
          />
          <p>DC POWER VISA</p>
        </div>
        <!-- end card -->
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Shop",
};
</script>

<style lang="scss">
#shop-section {
  height: 130px;
  background: rgb(0, 132, 255);
  color: #fff;

  .buy-image {
    width: 40px;
    margin-right: 15px;
  }
}
</style>