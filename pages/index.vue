<template>
  <section class="container">
    <header class="section">
      <h1 class="title">Hi there!</h1>
      <p class="text">
        My name is Emre and I am an aspiring web developer who has been 
        teaching himself how to code since the spring of 2016. 
      </p>
    </header>
    <main class="section">
      <div class="col">
        <h2 class="subtitle">ABOUT ME</h2>
        <p>
          I am a Master student in Social Sciences at Humboldt University Berlin 
          and I am about to finish my studies in the summer of 2018. Apart from my passion for coding, I 
          love anything DIY, cooking great food, traveling and working out regularly.
        </p>
        <p> 
          Already since I was a teenager I have always 
          played around with the web, building some simple projects and setting up simple Wordpress 
          or Joomla systems. In the spring of 2016 I decided to go all in on coding and I have not 
          looked back since!
        </p>
      </div>
      <div class="col">
        <h2 class="subtitle">MY LEARNING JOURNEY</h2>
        <p>
          I started out with lots of tutorials and after one year I was able to do a 6-month  
          internship at the Copenhagen-based consulting company <a href="http://ogtal.dk" class="text-link">
          <b>Analyse & Tal</b></a>. Here I introduced the use of frontend libraries (Vue) and 
          worked independently on a large experimental data-science project called <a href="https://likeview.surge.sh" class="text-link"><b>LikeView</b></a>.
        </p>
        <p>
          I have been privileged to attend a number of conferences, in part through helping as a volunteer or receiving a scholarship. 
          All of these conferences have been extraordinary experiences that have helped me a lot on my journey. In the past year I have attended 
          the following conferences: <span style="font-style: italic">Fullstack London 2017, Coldfront Copenhagen 2017, JSConf Budapest 2017, CSSconf EU 2018, 
          JSconf EU 2018, Fullstack London 2018.</span>
        </p>

      </div>
      <div class="col">
        <h2 class="subtitle">TECHNOLOGIES</h2>
        <p><b>Core: </b>HTML/CSS, Javascript</p>
        <p><b>Frontend: </b> Vue, Nuxt, React</p>
        <p><b>Backend: </b> Node/Express</p>
        <p><b>DB: </b> MongoDB, GraphQL</p>
        <p><b>Cloud: </b>Netlify, Heroku, Google Cloud, AWS</p>
        <p><b>Others: </b>D3.js, Sketch</p>
      </div>
      <div class="col">
        <h2 class="subtitle">GET IN TOUCH</h2>
        <div class="logo-container">
          <a href="mailto:creagas@googlemail.com" target="blank">
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
}
</style>
