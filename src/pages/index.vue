<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div rd-2 p-2 p-x-5 text-8 color-white class="email_box">
        639293382@qq.com
      </div>
    </div>
  </div>
</template>
<style lang="css" scoped>
.email .email_box {
  background: linear-gradient(119.46deg, rgba(189, 209, 255, 1) 0%, rgba(239, 166, 255, 1) 58.34%, rgba(253, 222, 255, 1) 100%);
}
</style>