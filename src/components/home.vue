<template>
  <div class="home">
    
    <div class="swiper-container" ref="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <zero @slideTo="slideTo"></zero>
            </div>
            <div class="swiper-slide">
                <one></one>
            </div>
            <div class="swiper-slide">
                <two></two>
            </div>
            <div class="swiper-slide">
                <three></three>
            </div>
            <div class="swiper-slide">
                <four></four>
            </div>
            <div class="swiper-slide">
                <five></five>
            </div>
            <div class="swiper-slide">
                <six></six>
            </div>
        </div>
    </div>

  </div>
</template>

<script>
import Zero from '@/components/zero/zero'
import One from '@/components/one/one'
import Two from '@/components/two/two'
import Three from '@/components/three/three'
import Four from '@/components/four/four'
import Five from '@/components/five/five'
import Six from '@/components/six/six'

export default {
  name:'home',
  components:{
      Zero,
      One,
      Two,
      Three,
      Four,
      Five,
      Six
  },
  data() {
      return {
          
      }
  },
  mounted() {
      setTimeout(() => {
          this.mySwiper = new Swiper('.swiper-container', {
              onInit: function(swiper) { 
                  swiperAnimateCache(swiper); 
                  swiperAnimate(swiper); 
              },
              onSlideChangeEnd: function(swiper) {
                  swiperAnimate(swiper); 
              }
          })        
      },20)
  },
  methods:{
      slideTo(index) {
          let interval = 800;
          if(index >=3 && index <= 4) {
              interval = 1500
          }else if(index >= 5 && index <= 6){
              interval = 2000
          }
          this.mySwiper.slideTo(index, interval)
      }
  }
}
</script>

<style lang="stylus" scoped>
.home
    width 1080px
    height 1920px
    margin 0 auto
    background #1c314d
</style>

