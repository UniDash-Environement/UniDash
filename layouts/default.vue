<script setup lang="ts">

</script>

<template>
<Background />
<FlexRow>
  <MenuLeft />
  <FlexColumn class="page">
    <MenuTop />
    <FlexColumn class="content">
      <slot />
    </FlexColumn>
  </FlexColumn>
</FlexRow>
</template>

<style lang="scss">
.page {
  width: calc(100vw - 290px);
  height: 100vh;

  > .content {
    margin: 10px;
    overflow-y: scroll;

    height: calc(100vh - 58px);
    width: calc(100% - 7px);
  }

  * {
    color: rgba(238, 238, 238, 0.6);
  }
}
</style>