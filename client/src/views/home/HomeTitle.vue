<template>
  <div class="home-title">
    <div class="home-title__info">
      <VanImage
        width="20"
        height="20"
        round
        src="https://fastly.jsdelivr.net/npm/@vant/assets/cat.jpeg"
      />
      <Button plain type="danger">测试</Button>
    </div>
  </div>
</template>

<script setup>
  import { Image as VanImage, Button } from 'vant';
</script>