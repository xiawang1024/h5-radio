<template>
    <div class="six">
        <div class="hd">
            <div class="title ani" swiper-animate-effect="zoomInDown" swiper-animate-duration="0.75s" swiper-animate-delay="0s"></div>
            <div class="title-text ani" swiper-animate-effect="lightSpeedIn" swiper-animate-duration="0.5s" swiper-animate-delay="0.75s"></div>
        </div>
        <div class="text-wrap">
            <div class="text ani" swiper-animate-effect="zoomIn" swiper-animate-duration="0.25s" swiper-animate-delay="0.5s"></div>
            <div class="text1 ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="0.5s" swiper-animate-delay="1s"></div>
            <div class="text2 ani" swiper-animate-effect="bounceInLeft" swiper-animate-duration="0.5s" swiper-animate-delay="1.5s"></div>
        </div>
        <div class="weixin-wrap">
            <div class="scroll1 ani" swiper-animate-effect="wxScroll" swiper-animate-duration="6s" swiper-animate-delay="1.5s"></div>
            <div class="scroll2 ani" swiper-animate-effect="wxScroll" swiper-animate-duration="5.5s" swiper-animate-delay="1s"></div>
            <div class="scroll3 ani" swiper-animate-effect="wxScroll" swiper-animate-duration="5s" swiper-animate-delay="0.75s"></div>
            <div class="little-wrap">
                <div class="little ani" swiper-animate-effect="bounceInUp" swiper-animate-duration="0.5s" swiper-animate-delay="0.5s"></div>
                <div class="antenna ani" swiper-animate-effect="fadeInUp" swiper-animate-duration="1.5s" swiper-animate-delay="1s"></div>
            </div>
        </div>
        <div class="voice ani" swiper-animate-effect="rollIn" swiper-animate-duration="0.5s" swiper-animate-delay="2s"></div>
        <div class="pages ani" swiper-animate-effect="flipInY" swiper-animate-duration="0.5s" swiper-animate-delay="2s"></div>
    </div>
</template>

<script>
export default {
    name:'six'
}
</script>

<style lang="stylus" scoped>
.six
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
        position absolute
        top 163px
        left 302px
        .title
            position absolute
            top 0
            left 0
            width 478px
            height 120px
            background url('./title.png') center center no-repeat
        .title-text
            position absolute
            top 148px
            left 45px
            width 403px
            height 102px
            background url('./title-text.png') center center no-repeat
    .text-wrap  
        position absolute
        top 581px
        left 217px
        .text
            position absolute
            top 0
            left 0
            width 686px
            height 435px
            background url('./text.png') center center no-repeat
        .text1
            position absolute
            top -19px
            left 382px
            width 233px
            height 54px
            background url('./text1.png') center center no-repeat
        .text2
            position absolute
            top 66px
            left 7px
            width 233px
            height 54px
            background url('./text2.png') center center no-repeat
    .weixin-wrap
        position absolute
        bottom 135px
        left 0
        width 1080px
        height 604px
        .scroll1
            position absolute
            top 397px
            left 0px
            width 1117px
            height 78px
            background url('./scroll1.png') center center no-repeat
        .scroll2
            position absolute
            top 270px
            left 130px
            width 981px
            height 40px
            background url('./scroll2.png') center center no-repeat
        .scroll3
            position absolute
            top 82px
            left 46px
            width 1365px
            height 49px
            background url('./scroll3.png') center center no-repeat
        .little-wrap
            position absolute
            top 0
            left 243px
            width 594px
            height 604px
            .little 
                position absolute
                z-index 100
                top 0
                left 0
                width 594px
                height 604px
                background url('./radio.png') center center no-repeat
            .antenna
                position absolute
                top -136px
                left 135px
                width 25px
                height 175px
                background url('./antenna.png') center center no-repeat
    .voice
        position absolute
        top 594px
        left 47px
        width 93px
        height 124px
        background url('./voice.png') center center no-repeat
    .pages
        position absolute
        top 370px
        left 911px
        width 152px
        height 154px
        background url('./pages.png') center center no-repeat
</style>

