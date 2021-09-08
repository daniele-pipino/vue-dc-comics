<template>
  <div id="app">
    <Header />
    <Jumbo />
    <Main />
    <Shop />
    <Footer />
  </div>
</template>

<script>
// App file
import Header from "@/components/Header.vue";
import Jumbo from "@/components/Jumbo.vue";
import Main from "@/components/Main.vue";
import Shop from "@/components/Shop.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Jumbo,
    Main,
    Shop,
    Footer,
  },
};
</script>

<style lang="scss">
// utilities
body {
  height: 100vh;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}

.container {
  width: 1100px;
  margin: 0 auto;
  height: 100%;
}

.d-flex {
  display: flex;
}

.space-between {
  justify-content: space-between;
}

.align-center {
  align-items: center;
}

.btn {
  text-decoration: none;
  padding: 15px 10px;
  color: rgb(255, 254, 254);
  border: 1px solid blue;
}
</style>
