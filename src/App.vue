<template lang="pug">

div#nav 
  Navbar 
  router-view
  Footer

</template>
<script>
import Footer from "./components/Footer";
import Navbar from './components/Navbar'
export default {
  components: {
    Footer,Navbar  
  },
};
</script>

<style lang="scss">
body {
  background: #000000;
  color: #ffffff;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
