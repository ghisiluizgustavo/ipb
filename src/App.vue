<template>
  <header-default></header-default>
  <main-page></main-page>
</template>

<script>
import HeaderDefault from "@/components/layouts/HeaderDefault.vue";
import MainPage from "@/components/MainPage.vue";
export default {
  components: {
    HeaderDefault,
    MainPage
  }
}
</script>

<style>
  * {
    padding: 0;
    margin: 0;
    font-family: "Roboto Light", sans-serif;
    font-weight: 500;
  }
</style>
