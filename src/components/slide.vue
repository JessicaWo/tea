<template>
  <div class="block">
    <el-carousel>
      <el-carousel-item v-for="(item,index) in imgList" :key="index">
        <img :src="item"/>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>
<script>
  export default {
    data () {
      return {
        imgList: [
          require('../assets/images/banner5.jpg'),
          require('../assets/images/banner5.jpg'),
          require('../assets/images/banner5.jpg'),
          require('../assets/images/banner5.jpg')
        ]
      }
    }
  }
</script>
<style>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 150px;
    margin: 0;
  }

  .el-carousel__item img {
    height: 100%;
    width: 100%;
  }

  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }

  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
</style>
