<template>
<div>
 <home-header></home-header>
 <home-swpier></home-swpier>
</div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwpier from './components/Swiper'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwpier
  }
}
</script>

<style>

</style>
