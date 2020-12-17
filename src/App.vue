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
  color: orange;
}

#nav a.router-link-exact-active {
  color: orange;
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
</style>
