<script lang="ts" setup></script>

<template>
  <div class="message">
    <h1>Attention!</h1>
    <p>Please install the VPN App to continue watching in safe mode</p>
    <hr class="full-width" />
    <p class="label">Install</p>
  </div>
</template>

<style lang="scss" scoped>
.message {
  background-color: white;
  border-radius: 1rem;
  padding: 1.5rem 0;
  text-align: center;
  line-height: 2.4rem;

  & h1 {
    font-size: 2.4rem;
    font-weight: 500;
  }
  & p {
    padding: 0 2.5rem;
    font-size: 1.6rem;
  }

  .label {
    margin: 0;
    text-decoration: none;
    font-size: 2.4rem;
    // font-weight: 500;
    color: cornflowerblue;
    padding: 0.8rem 0 0;
    display: block;
  }

  & hr {
    border: none;
    height: 0.1rem;
    background-color: darkgray;
    box-sizing: content-box;
  }
}
</style>
