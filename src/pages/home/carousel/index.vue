<script setup lang="ts">

</script>

<template>
  <div>
    <el-carousel
        height="700px"
    >
      <el-carousel-item
          v-for="item in 4"
          :key="item"
      >
        <img src="../../../assets/images/web-banner-1.png" alt="">
      </el-carousel-item>
    </el-carousel>
  </div>
</template>

<style scoped lang="scss">

</style>
