<template>
<v-container class="d-flex-column home-container">
 <div class="text-h2 text-uppercase  text-center divtitle d-flex align-end justify-center ma-5">
  <div>Нова инжиниринг</div> 
  </div>
<v-divider></v-divider>
<div class="text-h4 text-center divtitle">
  <div class="ma-4">
    Веб-интегрированнный BIM
  </div>
  <div class="ma-4">
    Лазерное сканирование и фотограмметрия в строительстве
  </div>
  </div> 
</v-container>
</template>
<script>
export default {
  name: 'IndexPage'
}
</script>
<style lang="scss">
@import '@/assets/main';
  
  .divtitle  {
    color: $primary-dark-color;
    height: 30vh;
  }
  
</style>
