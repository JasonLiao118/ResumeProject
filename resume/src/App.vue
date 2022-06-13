<template>
  <div id="app">
    <nav>
      <router-link to="/" class="nav-link">Home</router-link> |
      <router-link to="/about" class="nav-link">About</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}

nav {
  padding: 30px;
  justify-content: center;
  align-content: center;
  align-items: center;
}

nav a {
  font-weight: bold;
  color: white;
  margin-left: 2rem;
  margin-right: 2rem;
}

nav a.router-link-exact-active {
  color: #2fd188;
}
.nav-link {
  font-size: 3rem;
}
</style>
