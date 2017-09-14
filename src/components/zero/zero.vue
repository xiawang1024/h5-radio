<template>
    <div class="zero">
        <div class="hd">
            <div class="title ani" swiper-animate-effect="bounceInDown" swiper-animate-duration="1s" swiper-animate-delay="0s"></div>
            <div class="title-text ani" swiper-animate-effect="lightSpeedIn" swiper-animate-duration="1s" swiper-animate-delay="0.5s"></div>
            <div class="hand ani" swiper-animate-effect="rollIn" swiper-animate-duration="1s" swiper-animate-delay="1.5s"></div>
        </div>
        <div class="link">
            <div class="hndt ani" @click="slideTo(1)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="0s"></div>
            <div class="wap ani" @click="slideTo(2)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="0.25s"></div>
            <div class="app ani" @click="slideTo(3)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="0.5s"></div>
            <div class="gongzhonghao ani" @click="slideTo(4)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="0.75s"></div>
            <div class="weibo ani" @click="slideTo(5)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="1.0s"></div>
            <div class="little ani" @click="slideTo(6)" swiper-animate-effect="bounceInLeft" swiper-animate-duration="1s" swiper-animate-delay="1.25s"></div>
        </div>
        <div class="person ani" swiper-animate-effect="bounceInRight" swiper-animate-duration="1s" swiper-animate-delay="0s">

        </div>
        <div class="earth animated infinite bounce ani" swiper-animate-effect="bounce" swiper-animate-duration="1s" swiper-animate-delay="1.5s">

        </div>
        <div class="stars">
            <div class="star1 animated infinite pulse"></div>
            <div class="star2 animated infinite pulse"></div>
            <div class="star3 animated infinite pulse"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'zero',
    methods:{
        slideTo(index) {
            this.$emit('slideTo', index)
        }
    }
}
</script>

<style lang="stylus" scoped>
.zero
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
        position absolute
        left 152px
        top 174px
        .title
            position absolute
            left 200px
            top 10px 
            width 556px
            height 138px
            background url('./title.png') center center no-repeat
        .title-text
            position absolute
            left 147px
            top 150px 
            width 675px
            height 124px
            background url('./title-text.png') center center no-repeat
        .hand
            position absolute
            left 0
            top 0 
            width 147px
            height 267px
            background url('./hand.png') center center no-repeat
    .link
        position absolute
        left 113px
        top 559px
        .hndt
            position absolute
            left 0
            top 0 
            width 380px
            height 150px
            background url('./hndt.png') center center no-repeat
        .wap
            position absolute
            left 0
            top 185px 
            width 370px
            height 120px
            background url('./wap.png') center center no-repeat
        .app
            position absolute
            left 0
            top 339px 
            width 350px
            height 120px
            background url('./app.png') center center no-repeat
        .gongzhonghao
            position absolute
            left 0
            top 493px 
            width 350px
            height 120px
            background url('./gongzhonghao.png') center center no-repeat
        .weibo
            position absolute
            left 0
            top 648px 
            width 350px
            height 120px
            background url('./weibo.png') center center no-repeat
        .little
            position absolute
            left 0
            top 801px 
            width 450px
            height 120px
            background url('./little.png') center center no-repeat
    .person
        position absolute
        z-index 1000
        left 523px
        top 660px
        width 514px
        height 1047px
        background url('./person.png') center center no-repeat
    .earth
        position absolute
        left 0
        bottom -30px
        width 1080px
        height 366px
        background url('./earth.png') center center no-repeat
    .stars
        position absolute
        left 0
        bottom 265px
        width 1080px
        height 220px
        .star1
            position absolute
            left 22px
            top 0
            width 36px
            height 33px
            background url('./star1.png') center center no-repeat
        .star2
            position absolute
            left 90px
            bottom 0
            width 78px
            height 78px
            background url('./star2.png') center center no-repeat
        .star3
            position absolute
            right 36px
            top 30px
            width 58px
            height 79px
            background url('./star3.png') center center no-repeat
</style>

