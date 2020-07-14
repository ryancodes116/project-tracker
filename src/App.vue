<template>
  <div id="app">Hello World</div>
</template>

<script>
export default {
  name: "App",
  components: {}
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6,
button,
li {
  font-family: "Barlow Condensed", sans-serif;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 100vh;
  font-family: "Barlow", sans-serif;
  font-size: 18px;
}
</style>
