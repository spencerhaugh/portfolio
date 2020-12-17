<template>
    <div class="project-page">
        <h1>// THE GOODS</h1>
        <div class="projects-container">
          <!-- Project One -->
          <div class="project-one project-tile">
            <img src="../assets/Projects/DontForget-1.png" alt="Image of Memory Game Project">
            <div class="buttons">
              <a href="https://spencerhaugh.github.io/memory-app/index.html" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/memory-app" target="_blank"><button class='github-code'>GITHUB CODE</button></a>
            </div>
          </div>
          <!-- Project Two -->
          <div class="project-two project-tile">
            <img src="../assets/Projects/Catabase-1.png" alt="Image of Catabase Project">
            <div class="buttons">
              <a href="https://enigmatic-island-67697.herokuapp.com/catabase" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/cats-app" target="_blank"><button class='github-code'>GITHUB CODE</button></a>
            </div>
          </div>
          <!-- Project Three -->
          <div class="project-three project-tile">
            <img src="../assets/Projects/FarmStan-1.png" alt="Image of Farm Stan Project">
            <div class="buttons">
              <a href="https://farm-stan-client.herokuapp.com/" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/farmstan-app" target="_blank"><button class='github-code'>GITHUB CODE</button></a>
            </div>
          </div>
          <!-- Project Four -->
          <div class="project-four project-tile">
            <img src="../assets/Projects/Hangry-1.png" alt="Image of Hangry Project">
            <div class="buttons">
              <a href="https://mystifying-mccarthy-7142e6.netlify.app/" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/leftovers-app" target="_blank"><button class='github-code'>GITHUB CODE</button></a>
            </div>
          </div>
        </div>
    </div>

</template>

<script>
export default {
  name: 'Projects',
};
</script>

<style scoped>
  img {
    max-width: 600px;
    border-radius: 20px;
  }
  .projects-container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  .project-tile {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    margin-top: 3%;
    margin-bottom: 3%;
    background-color: rgba(255, 225, 170, 0.4);
    padding: 4%;
    border-radius: 20px;
  }
  button {
    width: 200px;
    border: none;
    padding: 10px;
    margin-top: 5%;
  }
  .buttons {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  .live-site {
    background-color: orange;
    color: whitesmoke;
  }
  .github-code {
    background-color: rgb(95, 187, 115);
    color: whitesmoke;
  }
</style>
