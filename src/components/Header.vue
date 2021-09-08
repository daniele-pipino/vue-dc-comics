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
            <li v-for="(link, index) in links" :key="index">
              <a href="#">{{ link.text }}</a>
            </li>
          </ul>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
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
      padding: 36px 0;
      &:hover {
        border-bottom: 5px solid rgb(0, 162, 255);
      }
    }
  }
}
</style>