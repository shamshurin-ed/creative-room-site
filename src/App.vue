<script setup lang="ts">
import HomeLogo from "@/components/HomeLogo.vue";
</script>

<template>
  <div class="home">
    <HomeLogo />
  </div>
</template>

<style>
@import "@/assets/base.css";

.home {
  position: fixed;
  top: 0;
  left: 0;

  display: grid;
  place-content: center;
  place-items: center;
  width: 100%;
  height: 100%;
  background-color: var(--color-background);
}
</style>
