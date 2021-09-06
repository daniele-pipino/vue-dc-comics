<template>
  <footer id="top-footer">
    <!-- container -->
    <div class="container d-flex space-between">
      <div class="row d-flex">
        <!-- list -->
        <div class="col f-list">
          <ul>
            <h3>DC COMICS</h3>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Movie</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Video</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>
        <!-- list -->
        <div class="col f-list">
          <ul>
            <h3>DC</h3>
            <li><a href="#">Terms of use</a></li>
            <li><a href="#">Privacy policy</a></li>
            <li><a href="#">Ad choises</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">jobs</a></li>
            <li><a href="#">Subscription</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop help</a></li>
            <li><a href="#">Contact us</a></li>
          </ul>
        </div>
        <!-- list -->
        <div class="col f-list">
          <ul>
            <h3>SITES</h3>
            <li><a href="#">Terms of use</a></li>
            <li><a href="#">Privacy policy</a></li>
            <li><a href="#">Ad choises</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">jobs</a></li>
          </ul>
        </div>
        <!-- list -->
        <div class="col f-list">
          <ul>
            <h3>Shop</h3>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC collectibles</a></li>
          </ul>
        </div>
      </div>
      <div><img src="../assets/img/dc-logo-bg.png" alt="" /></div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Topfooter",
};
</script>

<style scoped>
#top-footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  color: #fff;
}

.col ul {
  padding: 20px;
}
li {
  list-style-type: none;
  padding: 3px 0;
}
a {
  text-decoration: none;
  color: rgb(175, 175, 175);
}
</style>