<script setup lang="ts">
defineOptions({
  name: "fontMonoton"
});
</script>
<template>
    <div class="monoton-regular">
        <slot />
    </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Monoton&display=swap');

.monoton-regular {
  font-family: "Monoton", sans-serif;
  font-weight: 400;
  font-style: normal;
}

</style>