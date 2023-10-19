<script setup lang="ts">
import { Ref, inject } from 'vue'

const name = inject<Ref<string>>('name')
</script>

<template>
  <div>我是子组件获取的name：{{ name }}</div>
</template>

<style scoped></style>
