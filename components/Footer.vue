<template>
  <div>
    <footer class="bg-blue-700 w-full">
      <div
        class="text-blue-100 mx-auto flex flex-col md:flex-row justify-center items-center"
      >
        <div class="ml-15">
          <a href="https://twitter.com/jitsem93" class="fab fa-twitter"></a>
          <a href="https://github.com/jitsem" class="fab fa-github"></a>
          <a
            href="https://www.linkedin.com/in/jitse-meulenijzer-872625175/"
            class="fab fa-linkedin"
          ></a>
          <a href="mailto:info@jitsem.be" class="fa fa-envelope"></a>
        </div>
        <p class="p-15 text-sm"><em>&copy; jitsem 2020</em></p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://use.fontawesome.com/releases/v5.14.0/css/all.css");

.fa {
  margin: 5px 15px;
  color: #ffffff;
  text-decoration: none;
}

.fa:hover {
  color: #d5d5d5;
}

.fab {
  margin: 5px 15px;
  color: #ffffff;
  text-decoration: none;
}

.fab:hover {
  color: #d5d5d5;
}
</style>
