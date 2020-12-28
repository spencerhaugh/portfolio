<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/projects">Projects</router-link> |
    <router-link to="/contact">Contact</router-link>
  </div>
  <router-view/>
</template>

<style>
.resume {
  background: #1c92d2;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #f12711, #f5af19);
  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #f12711, #f5af19);
  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background-size: 400%;
  animation: gradient ease-in-out 5s infinite;
}
@keyframes gradient {
  0% {
    background-position: 100%;
  }
  50% {
    background-position: 20%;
  }
  100% {
    background-position: 100%;
  }

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  font-size: 1.25em;
  color: #2c3e50;
}

a {
  color: #f5af19;
  cursor: pointer;
}

#nav a.router-link-exact-active {
  color: #f5af19;
}
a:hover {
  color: rgb(255, 188, 64);
}
a {
  text-decoration: none;
}
@font-face {
      font-family: "KCOraleSans";
      src: local("KCOraleSans"),
      url(./fonts/KCOraleSans.otf) format("opentype")
    }
    @media (max-width: 650px) {
  #title {
    font-size: 6rem;
    margin: 20px auto;
  }
  #nav {
    font-size: 0.75em;
  }
  #projects-container button {
    width: 100px;
  }
}
</style>
