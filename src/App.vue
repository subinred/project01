<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import MainHeader from "./components/MainHeader.vue";
import MainFooter from "./components/MainFooter.vue";
</script>
<template>
  <!-- 전체 레이아웃 -->
  <div class="main-wrap">
    <MainHeader class="main-header" />
    <div>컨텐츠영역</div>
    <MainFooter />
  </div>
</template>

<style scoped>
.main-wrap {
  width: 100%;
}
</style>
