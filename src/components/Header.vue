<template>
  <div>
    <!-- code start here -->
    <header>
      <div class="container">
        <div class="logo">
          <img src="@/assets/img/dc-logo.png" alt="" />
        </div>
        <div class="nav-bar">
          <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
          </ul>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
header {
  height: 100px;
  width: 100%;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px;
  .logo img {
    width: 80px;
  }
  .nav-bar ul {
    display: flex;
    li {
      list-style-type: none;
      margin-left: 25px;
    }
    a {
      color: black;
      text-decoration: none;
      font-size: 12px;
      padding: 30px 0;
    }
  }
}
</style>