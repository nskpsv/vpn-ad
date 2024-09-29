<script lang="ts" setup></script>

<template>
  <div class="row justify-end viewport__top-bar bar">
    <span class="bar__more">...</span>
    <svg
      width="20"
      height="20"
      viewBox="0 0 12 12"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M1 10.83L10.83 1"
        stroke="#fff"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
      />
      <path
        d="M10.83 10.83L1 1"
        stroke="#fff"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
      />
    </svg>
  </div>
</template>

<style lang="scss" scoped>
.bar {
  column-gap: 2rem;

  &__more {
    color: #fff;
    font-size: 2.3rem;
    line-height: 0.8rem;
  }
}
</style>
