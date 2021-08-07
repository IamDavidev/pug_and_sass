<template lang="pug">
div
    h1 hola mundo desde un componente de pug 
        span.span-h1  esto es un span dentro de una etiqueta 
        |esto es mas h1

    



</template>

<script>
export default {};
</script>

<style scoped lang="scss">
h1 {
  margin: 40px 0 0;
}
.span-h1{
    color:#00ffff;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
