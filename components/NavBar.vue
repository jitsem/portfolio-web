<template>
  <div class="flex justify-between flex-wrap mx-16 md:px-10">
    <Logo />
    <div>
      <ul class="flex">
        <li
          class="mx-3 text-3xl text-gray-700 no-underline lowercase hover:text-blue-700 transition duration-500"
        >
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li
          class="mx-3 text-3xl text-gray-700 no-underline lowercase hover:text-blue-700 transition duration-500"
        >
          <nuxt-link to="/blog">Blog</nuxt-link>
        </li>
        <li
          class="mx-3 text-3xl text-gray-700 no-underline lowercase hover:text-blue-700 transition duration-500"
        >
          <nuxt-link to="/portfolio">Portfolio</nuxt-link>
        </li>
        <li
          class="mx-3 text-3xl text-gray-700 no-underline lowercase hover:text-blue-700 transition duration-500"
        >
          <nuxt-link to="/projects">Projects</nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  color: #3d70b2;
}
</style>
