<template>
  <div id="app">
    <Navbar />
    <HeroSection />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import HeroSection from "./components/HeroSection";
export default {
  name: "App",
  components: {
    Navbar,
    HeroSection
  }
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
a {
  font-family: "Barlow Condensed", sans-serif;
}

ul {
  list-style: none;
  margin: 0;
}

a {
  text-decoration: none;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 100vh;
  font-family: "Barlow", sans-serif;
  font-size: 18px;
  overflow: hidden;
  padding: 3rem 0 7rem;
}

.container {
  width: 85%;
  margin: 0 auto;
}
</style>
