<script>
import AppHeader from "./components/AppHeader.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import CardList from "./components/CardList.vue";

export default {
  components: {
    AppHeader,
    AppJumbotron,
    CardList,
  },
};
</script>

<template>
  <AppHeader />
  <main>
    <AppJumbotron />
    <CardList />
  </main>
</template>

<style lang="scss">
@use "./assets/scss/general.scss";
</style>
