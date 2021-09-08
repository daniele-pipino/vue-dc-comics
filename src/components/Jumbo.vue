<template>
  <div class="jumbo">
    <div class="container">
      <a href="#" class="btn">CURRENT SERIES</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbo",
};
</script>

<style scoped lang="scss">
.jumbo {
  height: 350px;
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover;
  position: relative;
  .btn {
    background-color: #0b85ff;
    position: absolute;
    bottom: -25px;
    font-weight: bolder;
  }
}
</style>