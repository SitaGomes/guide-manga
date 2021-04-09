<template>
  <div id="root">
    <div class="h-container">
      <nav>
        <nuxt-link to="/Home">Home</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
@use './index.scss';
</style>