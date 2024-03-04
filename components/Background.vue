<script setup lang="ts">

</script>

<template>
<div class="backgroundImage">
  <div class="backgroundTopOverImage" />
  <div class="backgroundBottomOverImage" />
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
  background-size: cover;

  .backgroundTopOverImage {
    position: absolute;
    top: 0;
    height: 60%;
    left: 0;
    right: 0;

    background: linear-gradient(rgba(31, 41, 55, 0.8), rgba(31, 41, 55, 1));
    backdrop-filter: blur(0.6rem);
  }

  .backgroundBottomOverImage {
    position: absolute;
    bottom: 0;
    height: 40%;
    left: 0;
    right: 0;

    background: rgba(31, 41, 55, 1);
  }
}
</style>