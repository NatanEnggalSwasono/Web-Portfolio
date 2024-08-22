<template>
  <nav>
    <div class="logo">
      <router-link to="/"><h1>Naenswa<span>.</span></h1></router-link>
    </div>
    <ul class="menu">
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/about">Project</router-link></li>
      <li><router-link to="/about">Skill</router-link></li>
      <li><router-link to="/about">Contact</router-link></li>
    </ul>
  </nav>
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&display=swap');
body {
  background: #0f0f0f;
}

#app {
  font-family: "Roboto", sans-serif;
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
  z-index: 1000;
}

nav .menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav h1 {
  font-size: 1.8em;
  color: #fff;
  padding-bottom: 15px
}

nav h1 span {
  font-size: 1.8em;
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
