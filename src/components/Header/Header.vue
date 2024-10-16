<template>
  <div class="header">
    <div class="container">
      <div class="logo">
        <img src="../../assets/logo.png" alt="logo" class="logo__image" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "HeaderApp",
});
</script>

<style scoped lang="less">
  @import "./header.less";
</style>
