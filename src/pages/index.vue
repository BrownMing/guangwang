<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div rd-2 bg-black p-2 p-x-5 text-8 color-white class="email-content">
        zhangruihang0617@icloud.com
      </div>
    </div>
  </div>
</template>
<style>
.email-content {
  position: absolute;
    left: 101px;
    top: -33px;
}
</style>