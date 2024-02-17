<template>
  <div id="app">
    <portfolio></portfolio>
  </div>
</template>

<script>
import portfolio from "./components/portfolio.vue";
export default {
  name: "App",
  components: {
    portfolio,
  },
};
</script>

<style scoped>
#app {
  box-sizing: border-box;
  font-family: poppins;
  padding: 0;
  margin: 0;
  font-size: initial;
}

@media only screen and (max-width: 56.25em) {
  html {
    font-size: 50%;
  }
  body {
    padding: 0;
  }
}
@media only screen and(max-width: 75em) {
  html {
    font-size: 56.25%;
  }
}
@media only screen and (min-width: 112.5em) {
  html {
    font-size: 75%;
  }
}
</style>
