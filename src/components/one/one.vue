<template>
  <div class="one">
       <div class="hd">
         <div class="title ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
         <div class="title-text ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.5s" swiper-animate-delay="0.25s"></div>
       </div>
       <div class="text-wrap">
         <div class="text ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="0.5s" swiper-animate-delay="0.5s"></div>
         <div class="text1 ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="0.5s" swiper-animate-delay="1.5s"></div>
         <div class="qrcode ani" swiper-animate-effect="rotateIn" swiper-animate-duration="0.5s" swiper-animate-delay="1.0s"></div>
         <div class="border ani" swiper-animate-effect="bounceInLeft" swiper-animate-duration="0.5s" swiper-animate-delay="0.5s"></div>
         <div class="mouse ani" swiper-animate-effect="fadeIn" swiper-animate-duration="0.5s" swiper-animate-delay="1.5s"></div>
       </div>
       <div class="pc-wrap">
         <div class="pc ani" swiper-animate-effect="slideInLeft" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
         <div class="web ani" swiper-animate-effect="fadeIn" swiper-animate-duration="0.5s" swiper-animate-delay="0.5s"></div>
       </div>
       <div class="arrow ani" swiper-animate-effect="bounceInUp" swiper-animate-duration="2s" swiper-animate-delay="0s"></div>
  </div>
</template>

<script>
export default {
  name:'one'
}
</script>

<style lang="stylus" scoped>
.one
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
      position absolute
      top 163px
      left 246px
      .title
        position absolute
        top 0
        left 0
        width 599px
        height 120px
        background url('./title.png') center center no-repeat
      .title-text
        position absolute
        top 152px
        left 4px
        width 541px
        height 101px
        background url('./title-text.png') center center no-repeat
    .text-wrap
      position absolute
      top 550px
      left 0
      width 1080px
      .text
        position absolute
        top 85px
        left 167px
        width 756px
        height 309px
        background url('./text.png') center center no-repeat
      .text1
        position absolute
        top 280px
        left 456px
        width 473px
        height 57px
        background url('./text1.png') center center no-repeat
      .qrcode
        position absolute
        z-index 1000
        top 10px
        left 166px
        width 180px
        height 180px
        background url('./qrcode.png') center center no-repeat
      .border
        position absolute
        top 0px
        left 90px
        width 924px
        height 492px
        background url('./border.png') center center no-repeat
      .mouse
        position absolute
        top 425px
        left 815px
        width 117px
        height 138px
        background url('./mouse.png') center center no-repeat
    .pc-wrap
      position absolute
      bottom 88px
      left 120px
      width 839px
      height 690px
      .pc
        position absolute
        top 0px
        left 0px
        width 839px
        height 690px
        background url('./pc.png') center center no-repeat
      .web
        position absolute
        top 16px
        left 16px
        width 807px
        height 466px
        background url('./web.jpg') center center no-repeat
    .arrow
      position absolute
      top 354px
      left 853px
      width 94px
      height 176px
      background url('./arrow.png') center center no-repeat
</style>

