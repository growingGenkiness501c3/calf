<script setup lang="ts">
defineOptions({
  name: "fontRubikMoonrocks"
});
</script>
<template>
    <div class="rubik-moonrocks-regular">
        <slot />
    </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rubik+Moonrocks&display=swap');
.rubik-moonrocks-regular {
  font-family: "Rubik Moonrocks", sans-serif;
  font-weight: 400;
  font-style: normal;
}

</style>