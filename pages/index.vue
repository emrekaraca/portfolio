<template>
  <section class="container">
    <header class="section">
      <h1 class="title">Hi there!</h1>
      <p class="text">
        My name is Emre and I am an aspiring web developer who has been 
        teaching himself how to code since Mid-2016. 
      </p>
    </header>
    <main class="section">
      <div class="col">
        <h2 class="subtitle">ABOUT ME</h2>
        <p>
          I am a Master student in Social Science at Humboldt University Berlin 
          and I am about to finish my studies.
        </p>
      </div>
      <div class="col">
        <h2 class="subtitle">MY LEARNING JOURNEY</h2>
        <p> I am a Master student in Social Science at Humboldt University Berlin 
          and I am about to finish my studies. I am a Master student in Social Science at Humboldt University Berlin 
          and I am about to finish my studies. I am a Master student in Social Science at Humboldt University Berlin 
          and I am about to finish my studies. I am a Master student in Social Science at Humboldt University Berlin 
          and I am about to finish my studies.</p>
      </div>
      <div class="col">
        <h2 class="subtitle">TECHNOLOGIES</h2>
        <p>Vue.JS, React, Node.JS, MongoDB, GraphQL</p>
      </div>
      <div class="col">
        <h2 class="subtitle">Conferences</h2>
        <p>
          I have been privileged to attend a number of conferences, in part through helping as a volunteer or receiving a scholarship. 
          All of these conferences have been extraordinary experiences that have helped me a lot on my journey. In the past year I have attended 
          the following conferences: <span style="font-style: italic">Fullstack London 2017, Coldfront Copenhagen 2017, JSConf Budapest 2017, CSSconf EU 2018, 
          JSconf EU 2018, Fullstack London 2018</span>
        </p>
      </div>
    </main>
  </section>

</template>

<script>
export default {
}
</script>

<style scoped>
  .container {
    font-size: 16px;
    background: #f7df1e;
    min-width: 100vw;
    min-height: 100vh;
    /* font-family: Helvetica, Arial, sans-serif; */
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
      width: 80vw
    }
    .col {
      width: 48%;
    }
  }
  .title {
    font-size: 6rem;
    font-style: italic;
    text-transform: uppercase;
  }
  .text {
    font-size: 2rem;
  }
  .subtitle {
    margin-top: 40px;
    margin-bottom: 10px;
    border-bottom: 4px solid black;
    font-size: 2rem;
  }

</style>
