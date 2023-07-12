<script>
export default{
  data(){
    return {
      srcImg : './src/assets/cane.jpg',
    }
  }
}
</script>

<template>
  <div class="img-wrapper">
    <img :src="srcImg" alt="">
  </div>
</template>

<style>
  .img-wrapper{
    margin: 0 auto;
    max-width: 500px;
  }
  .img-wrapper img{
    width: 100%;
  }
</style>