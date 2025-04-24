<script setup>
import { RouterView } from 'vue-router';
import HelloWorld from './components/HelloWorld.vue';
import Navigation from "./components/navigation/index.vue";
</script>
<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <Navigation />
    </div>
  </header>
  <RouterView />
</template>
<style scoped lang="less">
@import url("./index.less");
</style>