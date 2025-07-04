<script setup lang="ts">
defineOptions({
  name: "fontFreckleFace"
});
</script>
<template>
    <div class="freckle-face-regular">
        <slot />
    </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Freckle+Face&display=swap');

.freckle-face-regular {
  font-family: "Freckle Face", system-ui;
  font-weight: 400;
  font-style: normal;
}
</style>