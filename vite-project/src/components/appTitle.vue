<script>
export default{
  data(){
    return{
      title: 'La mia prima App con Vite !'
    }
  }
}
</script>
<template>
    <div class="container">
        <h1>{{title}}</h1>
    </div>
</template>
<style scoped>
.container{
    width: 750px;
    margin: 0 auto;
    background-color: pink;
    color:cornflowerblue;
}
h1{
    text-align: center;
}

</style>