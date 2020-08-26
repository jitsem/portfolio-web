<template>
  <div class="main-container">
    <div v-for="blog in blogs" :key="blog.slug">
      <nuxt-link :to="`/blog/${blog.slug}`">{{ blog.title }}</nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const blogs = await $content("blogs").fetch();

    return {
      blogs,
    };
  },
};
</script>

<style scoped></style>
