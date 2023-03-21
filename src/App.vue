<script setup lang="ts">
import Member from './components/member.vue'
</script>

<template>
  <div>
    <!-- <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a> -->
    <h2 class="members">รายชื่อสมาชิกกลุ่ม</h2>
  </div>
  <Member msg="" />
</template>

<style scoped>

.members{
  color: rgb(25, 136, 221);
}
</style>
