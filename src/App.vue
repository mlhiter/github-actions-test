<script setup lang="ts">
import { onMounted, provide, ref, watch } from 'vue'
import Children from './components/Children.vue'
const name = ref('lcy')
provide('name', name)
</script>

<template>
  <Children />
</template>

<style scoped></style>
