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
    <div class="flex flex-col mb-5 -ml-12">
      <span class="text-xl font-bold m-l-1">
        Linux Club of Peking University
      </span>
      <span class="text-4xl font-bold"> 北京大学学生 Linux 俱乐部 </span>
    </div>
  </div>
</template>
