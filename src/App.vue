<script>
import AppHeader from "./components/AppHeader.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import CardList from "./components/CardList.vue";
import AppSection from "./components/AppSection.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppJumbotron,
    CardList,
    AppSection,
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <main>
    <AppJumbotron />
    <CardList />
    <AppSection />
  </main>
  <AppFooter />
</template>

<style lang="scss">
@use "./assets/scss/general.scss";
</style>
