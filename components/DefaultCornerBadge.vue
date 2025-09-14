<template>
  <div class="flex items-end absolute -bottom-5 -left-20 opacity-10 dark:opacity-25">
    <LightOrDark width="100" alt="some image">
      <template #dark="props">
        <img src="../assets/icon-dark.svg" v-bind="props" />
      </template>
      <template #light="props">
        <img src="../assets/icon-light.svg" v-bind="props" />
      </template>
    </LightOrDark>
  </div>
</template>
