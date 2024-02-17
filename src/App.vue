<script setup>
import Oray from './components/Oray.vue'
</script>

<template>
  <Oray />

  <div class="icons">
    <a href="https://github.com/xebion/oraymatik" title="Github Repo">
      <img src="./assets/icons/github.svg" alt="Github Repo">
    </a>
  </div>
</template>

<style scoped>
  .icons {
    position: absolute;
    width: 200px;
    height: 40px;
    right: 0;
    top: 0;
    display: flex;
    justify-content: right;
  }

  .icons > a {
    display: inline-block;
    height: 60px;
    margin: 10px 10px;
    opacity: .6;
    transition: 80ms ease-in-out all;
  }

  .icons > a:hover {
    opacity: 1;
  }

  .icons img {
    height: 40px;
    width: auto;
  }
</style>