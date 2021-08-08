<template lang="pug">
div
    h1  componente  
        span.span-h1 de 
        |PUG 
    ul
        li(v-for="i in personas") {{i}}  
div
    ul 
      li 
        a(href="#") valor 1
      li
        a(href="#") valor 2 
      li 
        a(href="#") valor 3 

</template>

<script>
export default {
  data() {
    return {
      personas: ["daniel", "oscar", "julio", "david", "brayan"],
    };
  },
};
</script>

<style scoped lang="scss">
$primary: #00ffff;
$secondary: #303030;
$inlinne: inline-block;
$non: none;
$separacion: 10px;
$bold: bold;

h1 {
  color: $primary;
  background: $secondary;
  &:hover{
    color:snow;
  }
}
div {
  padding: $separacion;
  ul {
    list-style-type: disc;
    li {
      color: $primary;
      font-weight: $bold;
      margin: $separacion;
      a {
        color: $primary;
        &:hover {
          background: #ff0000;
          color:white;
        }
      }
    }
  }
}
</style>
