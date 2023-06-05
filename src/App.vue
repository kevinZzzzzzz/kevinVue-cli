<!--
 * @Author: kevinZzzzzz
 * @Date: 2023-06-02 10:58:36
 * @version: 
 * @LastEditors: kevinZzzzzz
 * @LastEditTime: 2023-06-05 11:22:50
 * @Description: Do not Edit
 * @FilePath: \vue-ts-vite\src\App.vue
-->
<template>
  <DefaultLayout>
    <router-view></router-view>
  </DefaultLayout>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router';
import DefaultLayout from '@/layout/default.vue'
</script>

<style scoped lang="less">
</style>