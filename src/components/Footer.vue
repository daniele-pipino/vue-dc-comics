<template>
  <footer>
    <div id="top-footer">
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
            <ul>
              <h3>Shop</h3>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC collectibles</a></li>
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
        </div>
        <div class="logo">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div id="bottom-footer">
      <div class="container d-flex space-between align-center">
        <!-- Button -->
        <div>
          <a class="btn" href="#">SIGN UP NOW!!</a>
        </div>
        <!-- social -->
        <div class="d-flex align-center">
          <span>FOLLOW US</span>
          <img
            class="social-img"
            src="../assets/img/footer-facebook.png"
            alt=""
          />
          <img
            class="social-img"
            src="../assets/img/footer-twitter.png"
            alt=""
          />
          <img
            class="social-img"
            src="../assets/img/footer-youtube.png"
            alt=""
          />
          <img
            class="social-img"
            src="../assets/img/footer-pinterest.png"
            alt=""
          />
          <img
            class="social-img"
            src="../assets/img/footer-periscope.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
#top-footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  color: #fff;
  padding: 20px;
  height: calc(530px - 80px);
}

.col ul li {
  list-style-type: none;
  padding: 3px 0;
}
a {
  text-decoration: none;
  color: rgb(175, 175, 175);
}
/* bottom footer */

#bottom-footer {
  height: 100px;
  background-color: rgb(73, 72, 72);
  position: relative;
  align-items: center;
}
a {
  color: #fff;
}
.social-img {
  width: 30px;
  margin: 5px;
}
span {
  color: rgb(0, 132, 255);
  margin-right: 10px;
}
</style>