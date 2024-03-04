<script setup lang="ts">

</script>

<template>
<div class="backgroundImage">
  <div class="backgroundOverImage" />
</div>
</template>

<style scoped lang="scss">
.backgroundImage {
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  z-index: -999;

  background-image: url("assets/images/background.png");
  background-repeat: no-repeat;
  background-size: 100% 65%;
  background-color: rgba(34, 40, 49, 1);

  .backgroundOverImage {
    position: absolute;
    top: 0;
    height: 65%;
    left: 0;
    right: 0;

    background: linear-gradient(rgba(34, 40, 49, 0.8), rgba(34, 40, 49, 1));
    backdrop-filter: blur(1rem);
  }
}
</style>