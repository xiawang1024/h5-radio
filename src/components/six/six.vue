<template>
    <div class="six">
        <div class="hd">
            <div class="title"></div>
            <div class="title-text"></div>
        </div>
        <div class="text-wrap">
            <div class="text"></div>
            <div class="text1"></div>
            <div class="text2"></div>
        </div>
        <div class="weixin-wrap">
            <div class="scroll1"></div>
            <div class="scroll2"></div>
            <div class="scroll3"></div>
            <div class="little-wrap">
                <div class="little"></div>
                <div class="antenna"></div>
            </div>
        </div>
        <div class="voice"></div>
        <div class="pages"></div>
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
            left -60px
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

