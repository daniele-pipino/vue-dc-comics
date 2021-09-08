<template>
  <div class="comic-card">
    <img :src="comic.thumb" alt="comic.series" />
    <p>{{ comic.series }}</p>
  </div>
</template>

<script>
export default {
  name: "Comicscard",
  props: ["comic"],
};
</script>

<style scoped lang="scss">
.comic-card {
  flex-basis: 16%;
  p {
    padding-left: 3px;
  }
}
</style>