<script lang="ts" setup></script>

<template>
  <div class="row align-center progress">
    <div class="progress__track"></div>
    <div class="progress__head"></div>
  </div>
</template>

<style lang="scss" scoped>
.progress {
  position: relative;
  background-color: black;
  height: 0.2rem;

  &__track {
    height: 100%;
    width: 5%;
    background-color: white;
  }

  &__head {
    width: 1rem;
    height: 1rem;
    border-radius: 50%;
    background-color: white;
  }
}
</style>
