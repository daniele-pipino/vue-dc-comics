<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
// App file
import Header from "@/components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
