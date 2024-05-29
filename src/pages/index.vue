<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div rd-2 p-2 p-x-5 text-8 color-white class="email_text">
        639293382@qq.com
      </div>
    </div>
  </div>
</template>

<style scoped lang="css">
.email_text{
  background: linear-gradient(119.59deg, #22F07B 0%, #2BA3FF 100%);
}
</style>