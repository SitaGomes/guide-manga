<template>
  <div>
    <Header />
    <!-- Content of the page -->
    <nuxt />
  </div>
</template>

<script>
import Header from "~/components/Header/Header.vue";

export default {
  components: { Header },
};
</script>

<style>
</style>