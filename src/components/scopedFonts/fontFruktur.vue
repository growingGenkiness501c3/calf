<script setup lang="ts">
defineOptions({
  name: "fontFruktur"
});
</script>
<template>
    <div class="fruktur-regular">
        <slot />
    </div>
</template>
<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Fruktur:ital@0;1&display=swap');

.fruktur-regular {
  font-family: "Fruktur", system-ui;
  font-weight: 400;
  font-style: normal;
}

.fruktur-regular-italic {
  font-family: "Fruktur", system-ui;
  font-weight: 400;
  font-style: italic;
}

</style>