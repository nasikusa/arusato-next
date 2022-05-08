<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    {{ hoge }}
    <Button>hogehoge button</Button>
  </div>
</template>

<script lang="ts" setup>
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import Button from "@/components/Button";

const hoge = 20;
</script>
