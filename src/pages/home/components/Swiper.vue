<template>
    <div class="wrapper">
        <swiper :options="swiperOption">
            <swiper-slide v-for="item of swiperList" :key="item.id">
                <img
                    class="swiper-img"
                    :src="item.imgUrl"
                    />
            </swiper-slide>
            <div class="swiper-pagination"  slot="pagination"></div>
        </swiper>
    </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination'
      },
      swiperList: [{
        id: '001',
        imgUrl: 'https://img.mukewang.com/5b7407b5000159ba09360316.jpg'
      },
      {
        id: '002',
        imgUrl: 'https://img.mukewang.com/5b4c50e1000136fc18720632.jpg'
      }]
    }
  }
}
</script>
<style lang='stylus' scoped>
.wrapper >>> .swiper-pagination-bullet-active
    background: #fff
.wrapper{
    overflow: hidden;
    width: 100%;
    height: 0;
    paddind-bottom: 31.25%;
    background: #eee;
    .swiper-img{
        width: 100%;
    }
}
</style>
