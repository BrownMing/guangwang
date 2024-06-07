<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div rd-2 p-2 p-x-5 text-8 color-white>
        nooneypline@gmail.com </div>
    </div>
  </div>
</template>
<style scoped lang="css">
.email {
  opacity: 1;
  border-radius: 16px;
  background: radial-gradient(6.57% 50% at 50.14925373134328% 100%, #F5F5F5 0%, #F5F5F5 100%), linear-gradient(135deg, #FF5833 0%, #FF7C33 100%);
  backdrop-filter: blur(40px);
}
</style>