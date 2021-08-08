<template lang="pug">

div#nav 
  router-link(to="/") HOME   
    router-link(to="/about") ABOUT 
  router-view
  Footer

</template>
<script>
import Footer from "./components/Footer.vue";
export default {
  components: {
    Footer,
  },
};
</script>

<style lang="scss">
body {
  background: #000000;
  color: #ffffff;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  a {
    margin-right: 10px;
    font-weight: bold;
    color: #ffffff;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
