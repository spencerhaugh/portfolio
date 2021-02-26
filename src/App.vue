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
  background: -webkit-linear-gradient(to right, #f12711, #f5af19);
  background: linear-gradient(to right, #f12711, #f5af19);
  background-size: 400%;
  animation: gradient ease-in-out 5s infinite;
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
  transition: 0.4s ease;
}

a {
  color: #f5af19;
  cursor: pointer;
}

#nav a.router-link-exact-active {
  color: #f5af19;
}
#nav a:hover {
  color: #f5af19;
}
a {
  text-decoration: none;
}

button:hover {
  cursor: pointer;
  opacity: 0.9;
  transform: scale(0.98);
}
button:focus {
  outline: 4px solid transparent;
  /* Accessibilty */
}
.button:active {
  transform: scale(0.98)
}

/* Font import */
@import url('https://fonts.googleapis.com/css2?family=Bungee+Shade&display=swap');

/* Gradient Animation keyframes */
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

/* Responsiveness */
    @media (max-width: 768px) {
      #title {
        font-size: 4rem;
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
