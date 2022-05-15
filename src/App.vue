<template>
  <nav>
    <router-link to="/">home</router-link> |
    <router-link to="/work">work</router-link> |
    <router-link to="/about">about</router-link> |
    <router-link to="/contact">contact</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #50332c;
  background-color: #1d1f20;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #30577a;
  text-decoration:underline;
  text-decoration-style: wavy;
  text-decoration-color: red;
}

nav a.router-link-exact-active {
  color: #29a6e0;
  text-decoration: none;
}
</style>
