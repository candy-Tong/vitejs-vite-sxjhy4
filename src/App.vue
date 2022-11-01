<script setup>
import { ref } from 'vue';
// import 'vue-router';

const count = ref(0);
setInterval(() => {
  count.value++;
}, 1000);
</script>

<template>
  <h5>将 import 'vue-router'; 取消注释</h5>
  <h5>页面会刷新，count 会被重置</h5>
  <div>{{ count }}</div>
</template>
