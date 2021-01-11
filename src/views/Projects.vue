<template>
    <div class="project-page">
        <h1>// THE GOODS</h1>
        <div class="projects-container" id='projects-container'>

          <!-- Project Four -->
          <div class="project-four project-tile">
            <img src="../assets/Projects/hangry-app.png" alt="Image of Hangry Project">
            <div class="buttons">
              <a href="https://mystifying-mccarthy-7142e6.netlify.app/" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/leftovers-app" target="_blank"><button class='github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This projects goal was to learn and implement
                new technologies to my skillset, in a 1 week timeframe.
                I chose to implement Vue.js for the first time,
                along with a 3rd Party API.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> Vue,
                Node, Express, MongoDB,
                Client-side Rendering,
                3rd Party API, RESTful Routing, Responsive design
              </div>
          </div>

          <!-- Project Three -->
          <div class="project-three project-tile">
            <img src="../assets/Projects/farm-stan-app.png" alt="Image of Farm Stan Project">
            <div class="buttons">
              <a href="https://farm-stan-client.herokuapp.com/" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/farmstan-app" target="_blank"><button class='github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This was a group project built in 1 week using
                React with an Express/Node backend, including Authentication
                and using JWT tokens. I worked mainly on the
                front end design.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> React,
                Node, Express,
                MongoDB, MERN Stack, Client-side Rendering,
                RESTful Routing, Authentication, Responsive design
              </div>
          </div>

          <!-- Project Two -->
          <div class="project-two project-tile">
            <img src="../assets/Projects/catabase-app.png" alt="Image of Catabase Project">
            <div class="buttons">
              <a href="https://enigmatic-island-67697.herokuapp.com/catabase" target="_blank"><button class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/cats-app" target="_blank"><button class='github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This project uses server-side rendering
                and MongoDB to securely log in users and allow them to
                upload data. This is a full CRUD app, with Authentication.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> Node,
                Express, MongoDB, EJS, Sever-side Rendering,
                Authentication, RESTful Routing, Responsive design
              </div>
          </div>

          <!-- Project One -->
          <div class="project-one project-tile">
            <img src="../assets/Projects/dontforget-app.png" alt="Image of Memory Game Project">
            <div class="buttons">
              <a href="https://spencerhaugh.github.io/memory-app/index.html" target="_blank"><button  class='live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/memory-app" target="_blank"><button class='github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This project was an exercise in game logic
                and DOM manipulation. The goal was to code a game in 1 week,
                with win/loss logic using only HTML, CSS, and jQuery.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> jQuery, HTML,
                CSS, Responsive design
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
    width: 600px;
    width: 80%;
    border-radius: 20px;
    -webkit-box-shadow: 2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    -moz-box-shadow:    2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    box-shadow:         2px 2px 8px 0px rgba(70, 70, 70, 0.69);
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
    max-width: 55%;
    margin-top: 3%;
    margin-bottom: 3%;
    background-color: rgba(255, 225, 170, 0.4);
    padding: 2%;
    border-radius: 20px;
    -webkit-box-shadow: 2px 2px 12px 0px rgba(70, 70, 70, 0.69);
    -moz-box-shadow:    2px 2px 12px 0px rgba(70, 70, 70, 0.69);
    box-shadow:         2px 2px 12px 0px rgba(70, 70, 70, 0.69);
  }
  button {
    border: none;
    padding: 15px;
    margin-top: 15%;
  }
  .buttons {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 45%;
  }
  button:hover {
    cursor: pointer;
  }
  .live-site {
    background-color: orange;
    color: whitesmoke;
  }
  .github-code {
    background-color: rgb(95, 187, 115);
    color: whitesmoke;
  }
  .description {
    width: 50%;
    margin-top: 4%;
  }
  .tech {
    width: 50%;
    margin-top: 4%;
  }
  @media (max-width: 550px) {
    .project-tile {
      width: 80%;
      padding: 2%;
    }
    .tech {
      font-size: 0.75rem;
    }
    .buttons {
      flex-direction: column;
    }
  }
</style>
