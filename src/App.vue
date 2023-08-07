<script setup lang="ts">
import HospitalTop from "@/components/hospital_top/index.vue";
import HospitalBottom from "@/components/hospital_bottom/index.vue";
</script>

<template>
  <div class="container">
    <HospitalTop/>
    <div class="content">
      <router-view></router-view>
    </div>
    <hospitalBottom/>
  </div>

</template>

<style scoped lang="scss">
.container {
  display: flex;
  flex-direction: column;
  align-items: center;

  .content {
    width: 100%;
    min-height: 1300px;
  }
}
</style>
