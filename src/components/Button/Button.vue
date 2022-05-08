<template>
  <div class="p-5 text-white bg-orange-400">
    <slot>button text</slot>{{ hoge }}
  </div>
</template>

<script lang="ts" setup>
const hoge = 20;
</script>
