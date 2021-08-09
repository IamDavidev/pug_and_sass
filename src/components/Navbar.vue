<template lang="pug">
div.navbar 
    h1 navbar
    router-link(to="/principal")  Principal  
    router-link(to="/about")  Productos 
    router-link(to="/about")  registrarse
    router-link(to="/about")  help  

</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.navbar {
  display: flex;
  text-align: center;
  text-transform: uppercase;
  a {
    justify-content: flex-end;
    align-items: flex-start;
    color: #ff0000;
    margin-left: 10px;
    padding: 1px auto;

    &.router-link-exact-active {
      color: #00ffff;
    }
  }
}
</style>
