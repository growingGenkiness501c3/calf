<script setup lang="ts">
defineOptions({
  name: "fontUnifrakturCook"
});
</script>
<template>
    <div class="unifrakturcook-bold">
        <slot />
    </div>
</template>
<style scoped>

@import url('https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap');

.unifrakturcook-bold {
  font-family: "UnifrakturCook", cursive;
  font-weight: 700;
  font-style: normal;
}

</style>