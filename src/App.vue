<!--
 * @Author: jincheng
 * @Date: 2023-08-10 15:24:24
 * @FilePath: /vue3-webpack5-admin/src/App.vue
-->

<template>
  <div>
    <h2>webpack5-vue3-ts</h2>
    <img :src="smallImg" alt="小于10kb的图片" />
  </div>
</template>

<script setup lang="ts">
 import smallImg from './assets/imgs/lt.jpeg'
import "./app.less";
console.log(212112211221);
</script>
<style scoped></style>
