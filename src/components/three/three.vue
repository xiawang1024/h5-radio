<template>
    <div class="three">
        <div class="hd">
            <div class="title ani" swiper-animate-effect="rotateInDownLeft" swiper-animate-duration="0.75s" swiper-animate-delay="0s"></div>
            <div class="title-text ani" swiper-animate-effect="flipInY" swiper-animate-duration="1.5s" swiper-animate-delay="0.75s"></div>
        </div>
        <div class="text-wrap">
            <div class="text ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="1.5s" swiper-animate-delay="0s"></div>
            <div class="text1 ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="2.5s" swiper-animate-delay="0.5s"></div>
            <div class="text2 ani" swiper-animate-effect="bounceInUp" swiper-animate-duration="2.5s" swiper-animate-delay="0.5s"></div>
        </div>
        <div class="app-wrap">
            <div class="qrcode ani" swiper-animate-effect="fadeIn" swiper-animate-duration="1.5s" swiper-animate-delay="0.5s"></div>
            <div class="shadow ani" swiper-animate-effect="fadeIn" swiper-animate-duration="1.75s" swiper-animate-delay="0.75s"></div>
            <div class="app ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="2s" swiper-animate-delay="0.5s"></div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
.three
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
        position absolute
        left 271px
        top 157px
        .title
            position absolute
            left 0
            top 0
            width 480px
            height 147px
            background url('./title.png') center center no-repeat
        .title-text
            position absolute
            left 291px
            top 141px
            width 298px
            height 117px
            background url('./title-text.png') center center no-repeat
    .text-wrap
        position absolute
        left 114px
        top 556px
        .text
            position absolute
            left 0
            top 0
            width 866px
            height 355px
            background url('./text.png') center center no-repeat
        .text1
            position absolute
            left 64px
            top 69px
            width 237px
            height 54px
            background url('./text1.png') center center no-repeat
        .text2
            position absolute
            left 527px
            top 69px
            width 237px
            height 54px
            background url('./text2.png') center center no-repeat
    .app-wrap
        position absolute
        bottom 0
        left 173px
        width 731px
        height 843px
        .qrcode
            position absolute
            z-index 100
            left 295px
            top 0px
            width 180px
            height 180px
            background url('./qrcode.png') center center no-repeat
        .shadow
            position absolute
            z-index 50
            left 107px
            top 0px
            width 554px
            height 285px
            background url('./shadow.png') center center no-repeat
        .app
            position absolute
            left -42px
            top 235px
            width 731px
            height 609px
            background url('./app.png') center center no-repeat
</style>

