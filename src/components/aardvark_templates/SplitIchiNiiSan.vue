<script setup lang="ts">
defineOptions({
  name: "SplitIchiNiiSan"
});
</script>
<template>
  <div class="bg-sky-950/50 text-sky-50 flex flex-nowrap fascinate-inline-regular text-[33px]">
      <div class="w-full lg:w-3/6 p-4">
        <slot name="ichi"></slot>
      </div>
      <div class="w-full lg:w-2/6 p-4">
        <slot name="nii"></slot>
      </div>
      <div class="w-full lg:w-1/6 p-4">
        <slot name="san"></slot>
      </div>
  </div>
  <div class="bg-sky-500/50 text-sky-500 flex flex-nowrap fascinate-inline-regular text-[33px]">
      <div class="w-full lg:w-2/6 p-4">
        <slot name="uno"></slot>
      </div>
      <div class="w-full lg:w-2/6 p-4">
        <slot name="dos"></slot>
      </div>
      <div class="w-full lg:w-2/6 p-4">
        <slot name="tres"></slot>
      </div>
  </div>
  <div class="bg-sky-50/50 text-sky-950 flex flex-nowrap fascinate-inline-regular text-[33px]">
      <div class="w-full lg:w-1/6 p-4">
        <slot name="one"></slot>
      </div>
      <div class="w-full lg:w-2/6 p-4">
        <slot name="two"></slot>
      </div>
      <div class="w-full lg:w-3/6 p-4">
        <slot name="four"></slot>
      </div>
  </div>



</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fascinate+Inline&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap');



.work-sans-<uniquifier> {
  font-family: "Work Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}
.fascinate-inline-regular {
  font-family: "Fascinate Inline", system-ui;
  font-weight: 400;
  font-style: normal;
}

</style>