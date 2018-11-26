<template>
  <section class="container">
    <header class="section">
      <h1 class="title">Hi there!</h1>
      <p class="text">
        My name is Emre and I am a Berlin-based web developer.
      </p>
    </header>
    <main class="section">
      <div class="col">
        <h2 class="subtitle">ABOUT ME</h2>
        <p>
          Apart from being a web developer, I am also a Master student in Social Sciences at Humboldt University Berlin.
          Currently, I am in the process of finishing my studies and I will be completely done by the end of 2018. Apart from my passion for coding, I
          love anything DIY, cooking great food, traveling and working out regularly.
        </p>
        <p>
          Already since I was a teenager I have always
          played around with the web, building some simple projects and setting up Wordpress
          or Joomla systems. In the spring of 2016 I decided to go all in on coding and I have not
          looked back since!
        </p>
        <p>Apart from studying and coding, I have worked a variety of jobs over the past years. A major focus has been the field of youth education, where I have continuously worked with groups of children and teenagers for 10 years. During this time, I have facilitated pedagocial programs at the <a href="https://annefrank.de" class="text-link">Anne Frank Zentrum Berlin</a> and as part of the project <a href="https://dialogmachtschule.de/" class="text-link">Dialog Macht Schule</a> at several schools with special challenges in Neukölln, Wedding and Moabit. These experiences have thaught me many invaluable skills.</p>
      </div>
      <div class="col">
        <h2 class="subtitle">MY JOURNEY</h2>
        <p>
          I started out with lots of tutorials and after one year I was able to do a 6-month
          internship at the Copenhagen-based data-consulting company <a href="http://ogtal.dk" class="text-link">
            Analyse & Tal</a>. Here I introduced the use of a modern frontend framework (VueJS) and
          worked independently on a large experimental data-science project called <a href="https://likeview.surge.sh" class="text-link">LikeView</a>.
        </p>
        <p>Over the summer of 2018 I worked as a freelancer on a project with <a href="http://ogtal.dk" class="text-link">
            Analyse & Tal</a>. In this project, which was funded by the Google-DNI, we analyzed 8 years of data from the Danish parliament and made it accessible for the general public. I was the lead frontend developer responsible for the creation of <a href="https://kendditfolketing.dk" class="text-link">Kend Dit Folketing</a>. The project was built with VueJS.</p>
        <p>
          I have been privileged to attend a number of conferences, in part through helping as a volunteer or receiving a scholarship.
          All of these conferences have been extraordinary experiences that have helped me a lot on my journey. In the past year I have attended
          the following conferences: <span style="font-style: italic">Fullstack London 2017, Coldfront Copenhagen 2017, JSConf Budapest 2017, CSSconf and JSconf EU 2018, Vue London 2018, VueJS Roadtrip Berlin 2018.</span> Naturally, mere conference attendance has no say about actual skill level. But it definitely reflects my unbound curiousity and motivation to keep up with the latest developments in the field.
        </p>

      </div>
      <div class="col">
        <h2 class="subtitle">TECHNOLOGIES</h2>
        <p><b>Core: </b>HTML/CSS, Javascript</p>
        <p><b>Frontend: </b> VueJS, Vuex, Nuxt, React, Gatsby, Apollo</p>
        <p><b>Backend: </b> Node/Express</p>
        <p><b>DB: </b> MongoDB, GraphQL</p>
        <p><b>Cloud: </b>Netlify, Heroku, Google Cloud, AWS</p>
        <p><b>Others: </b>D3.js, Sketch/Figma</p>
      </div>
      <div class="col">
        <h2 class="subtitle">GET IN TOUCH</h2>
        <div class="logo-container">
          <a href="mailto:hi@emrekaraca.de" target="blank">
            <img src="@/assets/email.svg" alt="" class="logo">
          </a>
          <a href="https://twitter.com/HiEmreKaraca" target="blank">
            <img src="@/assets/twitter.svg" alt="" class="logo">
          </a>
          <a href="https://github.com/emrekaraca" target="blank">
            <img src="@/assets/github.svg" alt="" class="logo">
          </a>
          <a href="https://www.linkedin.com/in/hiemrekaraca/" target="blank">
            <img src="@/assets/linkedin.svg" alt="" class="logo last-logo">
          </a>
        </div>
      </div>
    </main>
  </section>

</template>

<script>
export default {};
</script>

<style scoped>
.container {
  font-size: 16px;
  background: #f7df1e;
  min-width: 100vw;
  min-height: 100vh;
  font-family: Helvetica, Arial, sans-serif;
  display: flex;
  align-items: center;
  flex-flow: column;
  padding-top: 20px;
  padding-bottom: 40px;
}
.section {
  width: 90vw;
  max-width: 1200px;
}
main {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.col {
  width: 100%;
}
@media screen and (min-width: 1000px) {
  .container {
    padding-top: 100px;
  }
  .section {
    width: 80vw;
  }
  .col {
    width: 48%;
  }
}
.title {
  font-size: 3rem;
  font-style: italic;
  text-transform: uppercase;
  margin: 0;
}
.text {
  font-size: 1rem;
}
p {
  margin-top: 1rem;
  margin-bottom: 0;
}
@media screen and (min-width: 370px) {
  .title {
    font-size: 4rem;
  }
  .text {
    font-size: 1.5rem;
  }
}

.subtitle {
  margin-top: 40px;
  margin-bottom: 10px;
  border-bottom: 4px solid black;
  font-size: 2rem;
}
.logo-container {
  display: flex;
  justify-content: space-between;
}
.logo {
  fill: black;
  width: 50px;
  height: 50px;
  margin-right: 20px;
}
.last-logo {
  margin-right: 0px;
}
.text-link {
  color: black;
  text-decoration: none;
  font-weight: 700;
}
</style>
