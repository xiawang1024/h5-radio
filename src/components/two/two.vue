<template>
    <div class="two">
        <div class="hd">
            <div class="title ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
            <div class="qrcode ani" swiper-animate-effect="flipInX" swiper-animate-duration="1.5s" swiper-animate-delay="0s"></div>
            <div class="title-text ani" swiper-animate-effect="lightSpeedIn" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
        </div>
        <div class="text-wrap">
            <div class="text ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
            <div class="text1 ani" swiper-animate-effect="bounceInLeft" swiper-animate-duration="2.5s" swiper-animate-delay="0.5s"></div>
            <div class="text2 ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="2.5s" swiper-animate-delay="0.5s"></div>
        </div>
        <div class="wap-wrap">
            <div class="phone ani" swiper-animate-effect="bounceInUp" swiper-animate-duration="1s" swiper-animate-delay="0.5s"></div>
            <div class="wap ani" swiper-animate-effect="fadeInDown" swiper-animate-duration="1s" swiper-animate-delay="0.5s"></div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
.two
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
        position absolute
        left 245px
        top 143px
        .title
            position absolute
            left 0
            top 0
            width 599px
            height 120px
            background url('./title.png') center center no-repeat
        .qrcode
            position absolute
            left 0
            top 168px
            width 180px
            height 180px
            background url('./qrcode.png') center center no-repeat
        .title-text
            position absolute
            left 180px
            top 187px
            width 403px
            height 102px
            background url('./title-text.png') center center no-repeat
    .text-wrap
        position absolute
        top 573px
        left 192px
        .text
            position absolute
            left 0px
            top 0px
            width 688px
            height 239px
            background url('./text.png') center center no-repeat
        .text1
            position absolute
            left 365px
            top 59px
            width 300px
            height 45px
            background url('./text1.png') center center no-repeat
        .text2
            position absolute
            left 0px
            top 59px
            width 300px
            height 45px
            background url('./text2.png') center center no-repeat
    .wap-wrap
        position absolute
        bottom 0
        left 169px
        width 742px
        height 1015px
        .phone
            position absolute
            left 0
            top 0
            width 742px
            height 1015px
            background url('./phone.png') center center no-repeat
        .wap
            position absolute
            left 35px
            top 174px
            width 674px
            height 864px
            background url('./wap.jpg') center center no-repeat
</style>

