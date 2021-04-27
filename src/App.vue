<template>
  <div id="app">
    <img alt="Vue logo" src="https://raw.githubusercontent.com/diink-studios/axink-landing/main/src/assets/axink_w_logo.png">
    <p>Multi-platform game engine for web developers.</p>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&family=Righteous&display=swap');
html, body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: url('./assets/background.jpg');
  background-size: cover;
  width: 100vw;
  height: 100vh;
  background-color: rgb(88, 88, 88);
  background-blend-mode: multiply;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
p {
  font-family: 'Open Sans', sans-serif;
  font-size: 20px;
  font-weight: 300;
  color: #ffffff;
}
</style>
