<template>
    <section class="project-page">
        <h1>// THE GOODS</h1>
        <div class="projects-container" id='projects-container'>

          <!-- Project Zero -->
          <article class="project-zero project-tile">
            <h2>Poorly Drawn Pokemon</h2>
            <h3>A full stack image hosting platform</h3>
            <a href="http://www.poorlydrawnpokemon.com" target="_blank">
              <img src="../assets/Projects/pokemon-app.png" alt="Color picker app">
            </a>
            <div class="buttons">
              <a href="http://www.poorlydrawnpokemon.com" target="_blank"><button  class='button live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/monsters" target="_blank"><button class='button github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This was built in NextJS, a server side rendering
                framework that uses React under the hood. It allows admins to upload files, and
                also features search functionality, and a dark mode switcher. It is written in
                TypeScript. I used a Postgres SQL database to store user and image data, and
                Cloudinary to host image file uploads, as well as Strapi, a headless CMS for
                easy admin for my client. It is also fully mobile-ready.
                This project is deployed via Railway.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> NextJS, React, TypeScript, Postgres, Strapi,
                Material UI, Railway
              </div>
          </article>

          <!-- Project One -->
          <article class="project-one project-tile">
            <h2>Palette Maker!</h2>
            <h3>A custom color palette creator</h3>
            <a href="https://cranky-murdock-697124.netlify.app/" target="_blank">
              <img src="../assets/Projects/color-app.png" alt="Color picker app">
            </a>
            <div class="buttons">
              <a href="https://cranky-murdock-697124.netlify.app/" target="_blank"><button  class='button live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/color-project" target="_blank"><button class='button github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This was a really fun project! This React project
                implements advanced React patterns and UI functionality (like drag and drop,
                copy to clipboard, and transitions).
                The app utilizes concepts like Higher Order Components, Context, and Reducers for
                state management in React, Drag and Drop libraries, MaterialUI for
                component styling, and more.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> React, Javascript, HTML,
                CSS, JSS, CRA, Material UI, Drag and Drop, React Transition Group, Responsive UI
                design
              </div>
          </article>

          <!-- Project Two -->
          <article class="project-two project-tile">
            <h2>Real Time #Dogecoin</h2>
            <h3>A real time stream of tweets about $DOGE</h3>
            <a href="https://dry-temple-34762.herokuapp.com/" target="_blank">
              <img src="../assets/Projects/doge-app.png" alt="Image of Memory Game Project">
            </a>
            <div class="buttons">
              <a href="https://dry-temple-34762.herokuapp.com/" target="_blank"><button  class='button live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/real-time-twitter-app" target="_blank"><button class='button github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This was a super fun project using Twitter's API to
                preform a search for tweets containing a specific hashtag, and returning those
                tweets in <em>real time</em> as they happen. This was achieved using socket.io
                and connecting with the Twitter API, and then manipulating the DOM in the browser
                with Javascript.
                I created a header svg image in Adobe Illustrator, and added some basic styling
                by integrating the site with with Bootstrap.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> Socket.io, Twitter API, Node, Express,
                Javascript, HTML, CSS, Bootstrap, Responsive design, DOM manipulation.
              </div>
          </article>

          <!-- Project Three -->
          <article class="project-three project-tile">
            <h2>Race Recaps</h2>
            <h3>A micro blogging social media app</h3>
            <a href="https://recaps-app.herokuapp.com/" target="_blank">
              <img src="../assets/Projects/recap-app.png" alt="Color picker app">
            </a>
            <div class="buttons">
              <a href="https://recaps-app.herokuapp.com/" target="_blank"><button  class='button live-site'>LIVE SITE</button></a>
              <a href="https://github.com/spencerhaugh/race-recaps" target="_blank"><button class='button github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This is a micro blogging app for post-event recaps
                from sports event participants to share the experience with fans, and each other.
                Authentication is enabled with OAuth for login via Google. The app is a server side
                rendering app, built with Node and Express, and rendering content with Handlebars.
                The app uses Google's API and Passport to authenticate users, and stores their
                data in the MongoDB database.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> Handlebars, Javascript, HTML,
                CSS, Node.js, Express, Google API, Materialize, MongoDB, NoSQL,
                Mongoose, Responsive UI design
              </div>
          </article>

          <!-- Project Four -->
          <article class="project-four project-tile">
            <h2>Wide Angle Podium</h2>
            <h3>A patreon-like support site for podcasts</h3>
            <a href="https://www.wideanglepodium.com/" target="_blank">
              <img src="../assets/Projects/wapn-app.png" alt="Image of Wide Angle Podium website">
            </a>
            <div class="buttons">
              <a href="https://www.wideanglepodium.com/" target="_blank"><button class='button live-site'>LIVE SITE</button></a>
            </div>
            <div class="description">
                <strong>Description:</strong> This fully deployed and revenue-generating site
                is built for a podcast network, built to collect
                recurring donations, and receiving data from multiple podcast RSS feeds.
                It is also integrated with the Stripe API and the Recurly API to process
                recurring monthly payments. There are complex form submissions to track donor
                activity, and secure pages for authorized users only.
              </div>
            <div class="tech">
                <strong>Technologies Used:</strong> Wordpress CMS, Payment processing,
                Stripe API, Recurly API, SSL, 3rd Party RSS feeds, Responsive design
              </div>
          </article>

        </div>
    </section>

</template>

<script>
export default {
  name: 'Projects',
};
</script>

<style scoped>
  img {
    max-width: 600px;
    width: 80%;
    border-radius: 20px;
    -webkit-box-shadow: 2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    -moz-box-shadow:    2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    box-shadow:         2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    transition: transform 0.3s ease;
  }
  img:hover {
    transform: scale(1.02);
  }
  h2 {
    font-family: 'Bungee Shade', Helvetica, Arial;
    font-size: 4rem;
    margin: 0 auto;
    transition: color 0.4s ease-in-out;
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
    background-color: rgba(238, 238, 238, 0.3);
    max-width: 55%;
    margin-top: 3%;
    margin-bottom: 3%;
    border: 1px solid #555;
    padding: 2%;
    border-radius: 20px;
    transition: background-color 0.6s ease;
  }
  .project-tile:hover {
    background-color: rgba(238, 238, 238, 0.6);

  }
  .project-tile:hover h2 {
    color: #f5af19;
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
  .live-site {
    background-color: orange;
    color: whitesmoke;
  }
  .github-code {
    background-color: rgb(95, 187, 115);
    color: whitesmoke;
  }
  .description, .tech {
    width: 50%;
    margin-top: 4%;
  }
  @media (max-width: 850px) {
    .buttons {
      flex-direction: column;
    }
    .project-tile {
      max-width: 70%;
    }
    .description {
      width: 80%;
      margin-top: 4%;
    }
    .tech {
      width: 80%;
      margin-top: 4%;
    }
    h2 {
    font-size: 3rem;
  }
  }
  @media (max-width: 550px) {
    .project-tile {
      max-width: 80%;
      padding: 2%;
    }
    .tech {
      font-size: 0.75rem;
    }
    h2 {
    font-size: 2.5rem;
    margin: 5px auto;
  }
  }
  @media (max-width: 400px) {
  .project-tile {
    max-width: 85%;
    padding: 2%;
  }
  h2 {
    font-size: 2rem;
    margin: 5px auto;
  }
  }
</style>
