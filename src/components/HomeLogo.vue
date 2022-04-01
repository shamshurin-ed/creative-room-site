<script setup lang="ts">
</script>

<template>
  <div class="logo">
    <div class="logo__square">
      <div class="logo__text-wrapper">
        <div class="logo__text">creative room</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Alumni+Sans&family=Baloo+Paaji+2&family=Baloo+Tammudu+2:wght@600&family=Lexend+Giga&family=Lexend+Zetta&family=Saira:wght@300&family=Smooch+Sans&family=Syne:wght@500&display=swap');

.logo {
  pointer-events: none;
}

.logo__text-wrapper {
  height: 24px;
  display: grid;
  place-content: center;
  place-items: center;
  background-color: var(--color-background);
}

.logo__text {
  color: var(--color-text);
  font-size: 20px;
  text-transform: uppercase;
  white-space: nowrap;
  line-height: 1;
  /*font-family: 'Alumni Sans', sans-serif;*/
  /*font-family: 'Baloo Paaji 2', cursive;*/
  /*font-family: 'Baloo Tammudu 2', cursive;*/
  /*font-family: 'Lexend Giga', sans-serif;*/
  /*font-family: 'Lexend Zetta', sans-serif;*/
  /*font-family: 'Saira', sans-serif;*/
  font-family: 'Syne', sans-serif;
}

.logo__square {
  display: grid;
  place-items: center;
  place-content: center;
  width: 80px;
  height: 80px;
  border: 2px solid var(--color-text);
}
</style>