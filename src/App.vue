<script setup>
// import { useUserstore } from './stores/modules/user'
// import { useUserstore } from '@/stores'

// const userStore = useUserstore()
</script>

<template>
  <!-- <div>
    <p>token:{{ userStore.token }}</p>
    <el-button type="primary" @click="userStore.setToken('xys')"
      >登录</el-button
    >
    <el-button type="success" @click="userStore.setToken('')">退出</el-button>
  </div> -->
  <router-view></router-view>
</template>

<style scoped></style>
