<script setup lang="ts">
import DefaultCornerBadge from "../components/DefaultCornerBadge.vue";
</script>

<template>
  <div class="slidev-layout default relative">
    <div class="my-auto w-full z-1">
      <slot />
    </div>
    <DefaultCornerBadge />
  </div>
</template>
