<script>
export default{
  data(){
    return{
      img: 'src/assets/img-1.jpeg'
    }
  }
}
</script>
<template>
    <div class="container">
        <div class="img">       
            <img :src="img" alt="img">
        </div>
    </div>
</template>
<style scoped>
.container{
    width: 700px;
    margin: 0 auto;
}
img{
    width: 100%;
}
</style>