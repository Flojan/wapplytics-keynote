<script setup lang="ts">
import { computed } from 'vue'

const pageNumber = computed(() => $slidev.nav.currentPage);
</script>

<template>
  <div class="absolute bottom-7 right-7">
    <h2>/{{ pageNumber > 9 ? pageNumber : "0" + pageNumber}}</h2>
  </div>
</template>
