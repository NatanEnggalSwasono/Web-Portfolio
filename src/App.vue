<template>
  <nav>
    <div class="logo">
      <router-link to="/"><h1>Naenswa<span>.</span></h1></router-link>
    </div>
    <ul class="menu">
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
    </ul>
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
  position: fixed;
  top: 0;
  left: 0;
  width: -webkit-fill-available;
  padding: 0px 80px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
  background: #0f0f0f;
}

nav .menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav h1 {
  font-size: 1.6em;
  color: #fff;
}

nav h1 span {
  font-size: 1.6em;
  color: #42b983;
}

nav .menu li {
  display: inline-block;
  margin-left: 20px;
}

nav a {
  text-decoration: none;
  font-weight: bold;
  color: #fff;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
