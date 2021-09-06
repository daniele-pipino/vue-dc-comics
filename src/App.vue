<template>
  <div id="app">
    <Header />
    <Main />
    <Shop />
    <Topfooter />
  </div>
</template>

<script>
// App file
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Shop from "@/components/Shop.vue";
import Topfooter from "@/components/Topfooter.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Shop,
    Topfooter,
  },
};
</script>

<style lang="scss">
// utilities
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  width: 1100px;
  margin: 0 auto;
}

.d-flex {
  display: flex;
}

.space-between {
  justify-content: space-between;
}

img {
  width: 100%;
}
</style>
