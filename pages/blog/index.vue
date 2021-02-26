<template>
  <div class="container mx-auto px-2 md:px-0 my-6">
    <div
      class="flex flex-wrap flex-col-reverse justify-evenly"
      v-for="blog in blogs"
      :key="blog.slug"
    >
      <nuxt-link
        class="py-10 px-10 rounded shadow-lg my-3 border-blue-900 border"
        :to="`/blog/${blog.slug}`"
        >{{ blog.title }}</nuxt-link
      >
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const blogs = await $content("blog").fetch();

    return {
      blogs,
    };
  },
};
</script>

<style scoped></style>
