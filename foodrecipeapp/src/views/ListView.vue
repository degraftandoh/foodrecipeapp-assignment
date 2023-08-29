<!-- 
<script setup>
import TheNavbarComponent from '@/components/TheNavbarComponent.vue'
import TheCardsComponent from '../components/TheCardsComponent.vue';

</script>


<template>
  <div class="topBar">
    <NavBar/>
    <div class="texts">
      <h3>What ingredients do you have?</h3>
      <div class="entry">
        <img src="@/assets/searchicon.svg" alt="" class="searchLogo">
        <text type="text" class="searchPanel" placeholder="noodles">
      </div>
    </div>
  </div>

  <TheCardsComponent/>
</template>


<style scoped>

.texts{
  font-size: 24px;
  font-weight: 700;
  line-height: 29px;
  color: #000000;
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  gap:30px
}

.entry{
 display: flex;
 background: #FFFFFF;
 border-radius: 11px;
 padding-left: 25.4px;
 gap: 27.69px;

}

.searchLogo{
  max-width: 14.375px;
  width:100%;
  max-height: 14.375px;
  height: 100%;
  border: 2px;
  border-radius: 11px;
  margin: auto 0;
}

.searchPanel{
  max-width: 576px;
  width:100%;
  max-height: 52px;
  height: 100%;
  border-radius: 11px;
  background: #FFFFFF;
  box-shadow: 0px 14px 24px -8px #B6540E1C;
  border: none;
  padding-top: 20px;
  padding-bottom: 20px;
}

.topBar{
  padding: 19px 20px 84px 19px;
  background-color: #fba465;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 67px;
}
 
</style>
 -->






 <script setup>
import TheNavbarComponent from '@/components/TheNavbarComponent.vue'
import { RouterLink, RouterView } from 'vue-router'

 </script>
 
 <template>
   <main>
     <div>
         <TheNavbarComponent />
         <div class="topBar">
             <h2>What ingredients do you have?</h2>
             <div class="entry">
                 <img src="@/assets/searchicon.svg">
             </div>
         </div>
         
     </div>
   </main>
 </template>
 
 <style>
 .topBar{
     background: #FF9F59;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     gap: 30px;
     border: 1px solid red;
     padding-top: 40px;
     padding-bottom: 78px;
 }
 .topBar h2{
     color: #000;
     font-family: IBM Plex Sans;
     font-size: 32px;
     font-style: normal;
     font-weight: 700;
     line-height: 100%;
     letter-spacing: -1.28px;
 }
 .entry{
     display: flex;
     padding: 16px 0px 16px 22px;
     gap: 16px;
     border-radius: 16px;
     background: #FBFBFB;
     align-items: center;
     width: 590px;
 
 }
 text{
     color: #000;
     font-family: IBM Plex Sans;
     font-size: 24px;
     font-style: normal;
     font-weight: 500;
     line-height: 100%; 
   
     border: none;
 }
 
 </style>
 

