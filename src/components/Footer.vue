<template lang="pug">

div.footer 
    h3 {{date}}  
        a(href='https://github.com/L-David-26') David Lezama 
        | &copy;
        
</template>

<script>
export default {
   name:"Footer",
   computed: {
       date:()=>{
           // => new Date().getFullYar();
           // const date = new Date().getFullYear();
           //return date 
           const year = new Date()
           return year .getFullYear()

       }
   },
}
</script>

<style  scoped lang="scss">
.footer{
    background: #00184b;
    padding:2px;
    width:90%;
    position:absolute;
    bottom:0;
    h3{
        color:#ff0000;
    a{
        color:snow
    }
    }
}
</style>

