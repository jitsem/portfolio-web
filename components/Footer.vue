<template>
  <div>
    <footer>
      <div class="footer-content">
        <div class="social-links">
          <a href="https://twitter.com/jitsem93" class="fab fa-twitter"></a>
          <a href="https://github.com/jitsem" class="fab fa-github"></a>
          <a
            href="https://www.linkedin.com/in/jitse-meulenijzer-872625175/"
            class="fab fa-linkedin"
          ></a>
          <a href="mailto:info@jitsem.be" class="fa fa-envelope"></a>
        </div>
        <p class="copyright"><em>&copy; jitsem 2020</em></p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://use.fontawesome.com/releases/v5.14.0/css/all.css");

footer {
  height: 2.5rem;
  width: 100%;

  background: #3d70b2;
}

.footer-content {
  color: #ffffff;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  flex-basis: 95%;
}

.social-links {
  margin: 15 auto 0 auto;
}

.copyright {
  padding: 15 15;
  font-size: 10px;
}

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
