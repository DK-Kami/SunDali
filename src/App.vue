<template>
  <div id="app">
    <the-header-app/>
    <the-main-app/>
  </div>
</template>

<script>
import TheHeaderApp from "./components/TheHeaderApp";
import TheMainApp from "./components/TheMainApp.vue";

export default {
  name: "App",
  components: {
    TheHeaderApp,
    TheMainApp
  }
};
</script>

<style lang="stylus">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
