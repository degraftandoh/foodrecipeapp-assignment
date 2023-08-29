
<script setup>
defineProps(["image", "name"]);
</script>

<template>
  <div class="Cards">
    <img :src="imaage" alt="picture"/>
    <p>{{ name }}</p>
  </div>
</template>

<style scoped>
.Cards {
  width: 285px;
  height: 270px;
  flex-shrink: 0;
  border-radius: 16px;
  background: #fff;
  box-shadow: 0px 24px 64px -16px rgba(0, 0, 0, 0.1);
}
</style>
