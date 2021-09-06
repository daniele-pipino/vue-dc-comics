<template>
  <div id="app">
    <Header />
    <Main />
  </div>
</template>

<script>
// App file
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
  },
};
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  width: 1000px;
  margin: 0 auto;
}
</style>
