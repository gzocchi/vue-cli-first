<template>
  <div id="app">
    <header>
      <VueImage />
      <PageTitle />
    </header>
    <main>
      <Hero />
    </main>
  </div>
</template>

<script>
import VueImage from "./components/VueImage.vue";
import PageTitle from "./components/PageTitle.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    VueImage,
    PageTitle,
    Hero,
  },
};
</script>

<style lang="scss">
body {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  height: 100vh;
  width: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #42b983;
  font-size: 20px;
}
header {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 20%;
}
main {
  height: 60%;
  width: 80%;
  margin: auto;
}
</style>
