<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <home-icons></home-icons>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
export default {
  components: {
    HomeIcons,
    HomeHeader,
    HomeSwiper
  },
  name: 'Home'
}
</script>

<style scoped>

</style>
