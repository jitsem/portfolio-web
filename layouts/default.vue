<template>
  <div class="container">
    <header />
    <Nuxt />
    <Footer />
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #7e7e7e;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

header {
  background: linear-gradient(to bottom, #3d70b2 50%, white 0%);
  height: 40px;
}

.container {
  position: relative;
  min-height: 100vh;
}

.accent {
  color: #3d70b2;
}

.main-container {
  width: 66%;
  margin: 60px auto 2.5rem auto;
}
</style>
