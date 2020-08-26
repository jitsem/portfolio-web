<template>
  <div class="main-container">
    <nuxt-content :document="portfolio"></nuxt-content>
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const portfolio = await $content("portfolio").fetch();

    return {
      portfolio,
    };
  },
};
</script>

<style scoped></style>
