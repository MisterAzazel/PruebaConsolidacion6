<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  margin-top: 0 !important;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #1f6ab6;
}

body, html {
  margin: 0; /* Elimina cualquier margen */
  padding: 0; /* Elimina cualquier padding */

}

nav {
  padding: 30px;
  background-color: #2c3e50;
  text-align: left;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

}

nav a {
  font-weight: bold;
  color: #ecf0f1;
  text-decoration: none;
  margin-right: 15px;
  transition: color 0.3s ease;
}

nav a.router-link-exact-active {
  color: #42b983;
}

button {
  background-color: #1abc9c;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  color: #fff;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #16a085;
}

h1 {
  font-size: 3rem;
  margin-top: 80px;
}

h2 {
  color: #3498db;
}

p {
  color: #bdc3c7;
}
</style>
