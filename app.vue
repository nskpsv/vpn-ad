<script lang="ts" setup></script>

<template>
  <div class="full-width player">
    <div class="column justify-between viewport">
      <ViewportTopBar />
      <PopupMessage class="viewport__message" />
      <ViewportBottomBar />
    </div>
    <ProgressBar />
    <SocialBar />
    <Teleport to="body">
      <a
        class="link"
        href="https://apps.apple.com/us/app/vpn-security-secure-shield/id6523430492"
        target="_blank"
      ></a>
    </Teleport>
  </div>
</template>

<style lang="scss" scoped>
.player {
  &__meta {
    background-color: #343537;
    padding: 1rem;
  }

  .viewport {
    background-color: black;
    padding: 1rem;
    aspect-ratio: 16 / 9;

    &__message {
      margin: 4rem 2rem;
    }
  }
}
</style>
