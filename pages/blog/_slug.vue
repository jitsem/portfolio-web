<template>
  <div>
    <article>
      <nuxt-content :document="blog"></nuxt-content>
    </article>
  </div>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const blog = await $content("blogs", params.slug).fetch();

    return {
      blog,
    };
  },
};
</script>

<style scoped></style>
