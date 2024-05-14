<template>
  <footer class="absolute top-0 left-0 right-0 p-2 color-gray flex justify-end">
    <template v-if="currentPage !== 1">
      <img width="40" src="/kitbag-logo-circle.svg" alt="kitbag-logo" />
    </template>
  </footer>
</template>

<script lang="ts" setup>
import { useNav } from '@slidev/client'

const {currentPage} = useNav()
</script>