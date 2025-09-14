<script setup lang="ts">
import CoverCornerBadge from "../components/CoverCornerBadge.vue";
</script>

<template>
  <div class="slidev-layout cover relative">
    <div class="my-auto w-full z-1">
      <slot />
    </div>
    <CoverCornerBadge />
  </div>
</template>
