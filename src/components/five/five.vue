<template>
    <div class="five">
        <div class="hd">
            <div class="title ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="0.5s" swiper-animate-delay="0s"></div>
            <div class="title-text ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="0.5s" swiper-animate-delay="0.5s"></div>
            <div class="qrcode ani" swiper-animate-effect="rotateIn" swiper-animate-duration="0.5s" swiper-animate-delay="0.8s"></div>
        </div>
        <div class="text-wrap">
            <div class="text ani" swiper-animate-effect="fadeIn" swiper-animate-duration="1.5s" swiper-animate-delay="0s"></div>
            <div class="text1 ani" swiper-animate-effect="bounceInLeft" swiper-animate-duration="0.5s" swiper-animate-delay="1s"></div>
            <div class="text2 ani" swiper-animate-effect="bounceInLeft" swiper-animate-duration="0.5s" swiper-animate-delay="1.5s"></div>
            <div class="text3 ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="0.5s" swiper-animate-delay="2s"></div>
        </div>
        <div class="weibo-wrap">
            <div class="border1 ani" swiper-animate-effect="bounceIn" swiper-animate-duration="1s" swiper-animate-delay="0.5s"></div>
            <div class="border2 ani" swiper-animate-effect="bounceIn" swiper-animate-duration="1s" swiper-animate-delay="1s"></div>
            <div class="border3 ani" swiper-animate-effect="bounceIn" swiper-animate-duration="1s" swiper-animate-delay="1.5s"></div>
            <div class="weibo">
                <div class="avatar ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.75s" swiper-animate-delay="2.0s"></div>
                <div class="weibo-title ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.5s" swiper-animate-delay="2.5s"></div>
                <div class="weibo-desc ani" swiper-animate-effect="bounceIn" swiper-animate-duration="0.5s" swiper-animate-delay="3s"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'five'
}
</script>

<style lang="stylus" scoped>
.five
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd 
        position absolute
        top 173px
        left 301px
        .title  
            position absolute
            top 0
            left 0
            width 478px
            height 120px
            background url('./title.png') center center no-repeat
        .title-text  
            position absolute
            top 149px
            left 44px
            width 403px
            height 102px
            background url('./title-text.png') center center no-repeat
        .qrcode  
            position absolute
            top 305px
            left 156px
            width 180px
            height 180px
            background url('./qrcode.png') center center no-repeat
    .text-wrap
        position absolute
        top 765px
        left 181px
        .text
            position absolute
            top 0
            left 0
            width 721px
            height 275px
            background url('./text.png') center center no-repeat
        .text1
            position absolute
            top -39px
            left 68px
            width 179px
            height 70px
            background url('./text1.png') center center no-repeat
        .text2
            position absolute
            top 149px
            left 90px
            width 235px
            height 54px
            background url('./text2.png') center center no-repeat
        .text3
            position absolute
            top 149px
            left 390px
            width 235px
            height 54px
            background url('./text3.png') center center no-repeat
    .weibo-wrap
        position absolute
        bottom 0
        left 102px
        width 875px
        height 874px
        .border1
            position absolute
            top 0
            left 0
            width 875px
            height 874px
            background url('./border1.png') center center no-repeat
        .border2
            position absolute
            top 83px
            left 84px
            width 711px
            height 711px
            background url('./border2.png') center center no-repeat
        .border3
            position absolute
            top 148px
            left 149px
            width 581px
            height 581px
            background url('./border3.png') center center no-repeat
        .weibo
            position absolute
            top 243px
            left 306px
            .avatar
                position absolute
                top 0
                left 0
                width 240px
                height 240px
                background url('./avatar.png') center center no-repeat
            .weibo-title
                position absolute
                top 276px
                left 0
                width 256px
                height 48px
                background url('./weibo-title.png') center center no-repeat
            .weibo-desc
                position absolute
                top 353px
                left 2px
                width 252px
                height 28px
                background url('./weibo-desc.png') center center no-repeat
</style>

