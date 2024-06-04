<template>
  <nav>
    <router-link to="/"><img alt="Vue logo" src="../src/assets/logo.png"></router-link>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>

body {
  background: #0f0f0f;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}

nav {
  padding: 30px;
  background-color: aquamarine
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

nav img {
  width: 100px;
}
</style>
