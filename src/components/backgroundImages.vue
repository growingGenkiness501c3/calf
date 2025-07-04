
<script setup lang="ts">
defineOptions({
  name: "backgroundImages"
});
</script>

<style scoped>
.bg-layered-background {
  background-image: 
    url('/backgrounds/earth-33.png'),  
    url('/backgrounds/012.png'),
    url('/backgrounds/123.png'),
    url('/backgrounds/234.png'),
    url('/backgrounds/345.png'),    
    url('/backgrounds/456.png'),    
    url('/backgrounds/567.png'),
    url('/backgrounds/678.png'),
    url('/backgrounds/78a.png'),
    url('/backgrounds/89a.png'),
    url('/backgrounds/9ab.png'),
    url('/backgrounds/abc.png'),
    url('/backgrounds/bcd.png'),
    url('/backgrounds/cde.png'),
    url('/backgrounds/def.png'); /* base layer at the bottom */

  /* Positions for each image */
  background-position: 
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0;

  /* Repeat settings for each image */
  background-repeat: 
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat,
    repeat;

  /* Sizes for each image */
  background-size: 
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto,
    auto;
}
</style>

<template>
  <div class="bg-layered-background w-full h-full">
    <slot name="default"></slot>
  </div>
</template>
