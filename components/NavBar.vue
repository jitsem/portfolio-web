<template>
  <div class="top-bar">
    <Logo />
    <div class="nav-links">
      <ul>
        <li><nuxt-link to="/blog">Blog</nuxt-link></li>
        <li><nuxt-link to="/portfolio">Portfolio</nuxt-link></li>
        <li><nuxt-link to="/projects">Projects</nuxt-link></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.top-bar {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  width: 90%;
  margin: auto;
}

.nav-links ul {
  display: inline-flex;
  list-style: none;
}

.nav-links li {
  margin-left: 10px;
  margin-right: 10px;
}

.nav-links a {
  text-decoration: none;
  text-transform: lowercase;
  font-size: 20px;
  color: #7e7e7e;
}

.nav-links a:hover {
  color: #3d70b2;
  transition: 0.5s;
}
</style>
