<template>
  <footer class="absolute bottom-0 left-0 right-0 p-2 color-gray flex justify-between">
    <div>{{ currentPage }} / {{ slides.length }}</div>
    <div>router.kitbag.dev</div>
  </footer>
</template>

<script lang="ts" setup>
import { useNav } from '@slidev/client'

const {currentPage, slides} = useNav()
</script>