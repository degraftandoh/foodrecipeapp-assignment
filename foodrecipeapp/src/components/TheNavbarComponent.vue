
<script setup>
import { RouterLink } from 'vue-router'

</script>


<template>
<div class="navigationBar">
  <img src="@/assets/foodl.png" alt="picture">
  <div class="propertySearch">
    <div class="router">
      <RouterLink to="/"> Home </RouterLink>
      <RouterLink to ="/List"> Search </RouterLink>
  </div>
  </div>
</div>
</template>


<style scoped>
h5{
  padding: 12px 20px;
  background: #000000;
  color: #FFFFFF;
  border-radius: 3px;
  display: flex;
  text-align: center;
  width:111.6px;
  Height:48px;
  box-shadow: 0px 2px 2px 0px #00000026;
}

.propertySearch{
  display: none;
}

@media (min-width: 750px) {
  .propertySearch{
    display: flex;
    gap: 72px;
  }

  .navigationBar{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    color: #000000;
  }

  .router{
    display: flex;
    gap: 72px;
    text-decoration: none;
    color: #000000;
  }
}

</style>