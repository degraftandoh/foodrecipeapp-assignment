
<script setup>
import TheNavbarComponent from '@/components/TheNavbarComponent.vue';
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main>
    <TheNavbarComponent />
    <div class="parentContainer">
      <div class="heading">
        <h2>Find recipes for the ingredients you have on hand</h2>
        <RouterLink to="/list"><button>Search Now</button></RouterLink>
      </div>
      <div>
        <img src="@/assets/image1a.png">
      </div>
      
    </div>
  </main>
</template>

<style scoped>
main{
  background: #FF9F59;

}
.parentContainer{
  background-color: #fba465;
  padding: 19px 20px 67px 19px;
  display: flex;
  flex-direction: column;
  gap: 20px;
  
}
.heading{
  padding-top: 100px;
  display: flex;
  flex-direction: column;
  gap: 32px;
  align-items: flex-start;
}
.heading h2{
  color: #000;
  font-family: IBM Plex Sans;
  font-size: 48px;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;
  letter-spacing: -1.92px;

}
button{
  border-radius: 8px;
  background: #000;
  padding: 20px 60px;
  color: #FFF;
  font-family: IBM Plex Sans;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 130%;
  letter-spacing: -0.96px;
}
</style>




rentContainer{
  display: flex;
  justify-content: space-between;
  padding-left: 120px;
  padding-top: 50px;





















<!-- 
<script setup>
import TheNavbarComponent from '@/components/TheNavbarComponent.vue'
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
<div class="parentContainer">
  <TheNavbarComponent />
    <div class="heading">
      <div class="entry">
        <h2>Find recipes for the ingredients you have on hand</h2>
        <button><RouterLink to="/List">Search Now</RouterLink></button>
      </div>
      <img src="@/assets/image1a.png" alt="no picture" class="photo">
  </div>
  </div>
</template>

<style scoped>
button{
  max-width: 244px;
  width: 100%;
  max-height:72px;
  height:100%;
  padding:20px 60px;
  background: #000;
  font-size: 18px;
  font-weight: 500;
  line-height: 31px;
  text-align: center;
  color:#FFFFFF;
  border:none;
}

.entry{
  display: flex;
  flex-direction: column;
  gap: 10px;
  justify-content: center;
}

.entry h2{
  font-size: 24px;
  font-weight: 700;
  line-height: 29px;
  letter-spacing: -0.04em;
  text-align: left;
  color: #000;
}
.heading{
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.photo{
  max-width:248px;
  width:100%;
  max-height:229px;
  height:100%
}

.parentContainer{
  background-color: #fba465;
  padding: 19px 20px 67px 19px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

@media (min-width:750px) {
  .heading{
    display: flex;
    flex-direction: row;
    gap: 138px;
  }
  .entry h2{
   max-width:442px;
    width:100%;
    font-size: 48px;
    font-weight: 700;
    line-height: 62px;
    text-align: left;
    color: #000;
  }
}

</style> -->