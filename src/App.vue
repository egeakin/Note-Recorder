<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <h1>Enter a Note</h1>
    </nav>

    <router-view />

  </div>
</template>

<script>
import Skills from './components/Skills.vue'

export default {
  name: 'app',
  components: {
    Skills
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');

body {
  background-color: #EEEEEE;
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  padding-top: 50px;
    background-image: url(https://flipwallpapers.com/wallpapers/abstract-wallpaper-high-resolution-For-desktop-Wallpaper.jpg);

}
body, html {
  margin: 0;
  height: 100%;
}

#app {
  width: 50%;
  //background: yellow;
  //background-image: url(https://flipwallpapers.com/wallpapers/abstract-wallpaper-high-resolution-For-desktop-Wallpaper.jpg);

}

nav {
  padding: 20px 20px 20px 0;
}

h1 {
  margin-top: 60px;
  text-align: center;
  font: "Helvetica";
  color: white;
  font-size: 35px;
}

nav a {
  padding: 10px;
  text-decoration: none;
  background: #fff;
  border-radius: 3px;
  color: rgb(0, 110, 255);
  font-weight: bold;
  margin-right: 15px;
}
</style>
