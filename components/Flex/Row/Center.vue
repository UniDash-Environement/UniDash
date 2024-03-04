<script setup lang="ts">

</script>

<template>
<div class="flex">
  <slot />
</div>
</template>

<style scoped lang="scss">
.flex {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>