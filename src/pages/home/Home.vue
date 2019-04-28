<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <home-icons></home-icons>
    <home-recommand></home-recommand>
    <home-weekend></home-weekend>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
import HomeRecommand from './components/Recommand'
import HomeWeekend from './components/Weekend'
export default {
  components: {
    HomeWeekend,
    HomeRecommand,
    HomeIcons,
    HomeHeader,
    HomeSwiper
  },
  name: 'Home'
}
</script>

<style scoped>

</style>
