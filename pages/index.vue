<template>
  <div>
    <NavBar />
    <div class="main-container">
      <div class="title-section">
        <div class="titles">
          <h1>Software Developer</h1>
          <h2>Welcome to my website</h2>
        </div>
        <img
          src="../assets/programming1.svg"
          alt="Picture of man programming"
        />
      </div>
      <div class="intro-section">
        <p>
          Hi, I'm <b class="accent">Jitse</b>: Software devoloper, tweaker and
          general tech-enthusiast. I'm also a gamer, lover-of-cats, Lord of the
          Rings fan & hobbyist beer-brewer. I made this site to play around a
          bit with various web-related technologies. Feel free to take a look
          around! Continue reading below if you want to know a bit more about
          me. My various contact details are listed in the footer of this page.
          Please contact me if you want to collaborate on a certain project. You
          can also check out my blog for some awesome tech-stories.
        </p>
        <img src="../assets/hacking1.svg" alt="Picture of man hacking" />
      </div>
      <hr class="line-break" />
      <div class="skills-section">
        <h4>My skills</h4>
        <div class="skillset-container">
          <ul class="skillset-list">
            <li>NET ecosystem mastery: C#, WPF, C++/CLI, ...</li>
            <li>Proficient in General IT: Linux, Bash, SSH, Powershell, ...</li>
            <li>
              Articulate in other programming languages: Java, Qt, C, Python,
              ...
            </li>
            <li>
              Capable in Web Development: HTML, CSS, JavaScript, Vue, Nuxt, ...
            </li>
            <li>Expercience in website deployment: DNS, nginx, docker, ...</li>
            <li>Check out my full portfolio</li>
          </ul>
          <img src="../assets/coding1.svg" alt="Picture of man coding" />
        </div>
      </div>
      <hr class="line-break" />
      <div class="outro-section">
        <h4>Contact me</h4>
        <div class="outro-container">
          <img src="../assets//karikatuur.png" alt="karikatuur portret" />
          <p>
            Thank you for showing interest in my website. I hope you liked what
            you saw, because I had a lot of fun making this. My contact details
            are linked below, so if you have any question (or you want to work
            together on a project) please let me know. Also, don't forget to
            check out my blog and my other projects linked at the top. Enjoy the
            rest of your day! :)
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main-container {
  width: 66%;
  margin: 60px auto 0 auto;
}

.title-section {
  display: flex;
  flex-wrap: wrap;
  text-align: center;
  align-items: center;
  justify-content: center;
  margin: 50px 0px;
}

.title-section h2 {
  color: #3d70b2;
  font-size: 32;
}

.title-section h1 {
  font-size: 40;
}

.title-section img {
  margin-left: 5px;
  max-width: 50%;
}

.intro-section {
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-items: center;
}

.intro-section img {
  align-self: center;
  margin-top: 20px;
  max-width: 33.3%;
}

.intro-section p {
  text-align: center;
  margin: auto;
}

.skillset-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.skills-section h4 {
  text-align: left;
  margin-bottom: 20;
  margin-top: 10;
}

.skills-section ul {
  margin: 30px auto;
  overflow-wrap: break-word;
}
.skills-section img {
  align-self: center;
  margin-left: 10px;
  max-width: 33.3%;
}

.skills-section li {
  background: url("../assets/checkmark.svg") left center no-repeat;
  padding-bottom: 5px;
  padding-left: 30px;
  list-style-type: none;
}

.outro-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.outro-section {
  margin-bottom: 20px;
}

.outro-section img {
  align-self: center;
  margin-right: 10px;
  margin-bottom: 10px;
  margin-top: 10px;
  max-width: 33%;
}

.outro-section h4 {
  text-align: left;
  margin-bottom: 20;
  margin-top: 10;
}

.outro-section p {
  text-align: center;
}
</style>
