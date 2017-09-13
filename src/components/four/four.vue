<template>
    <div class="four">
        <div class="hd">
            <div class="title"></div>
            <div class="title-text"></div>
        </div>
        <div class="qrcode-wrap">
            <div class="qrcode"></div>
            <div class="text-wrap">
                <div class="text"></div>
                <div class="text1"></div>
                <div class="text2"></div>
                <div class="text3"></div>
                <div class="text4"></div>
            </div>
            <div class="border"></div>
        </div>
        <div class="weixin-wrap">
            <div class="weixin"></div>
            <div class="menu"></div>
            <div class="click"></div>
        </div>
    </div>
</template>

<script>
export default {
    name:'four'
}
</script>

<style lang="stylus" scoped>
.four
    position relative
    width 1080px
    height 1920px
    overflow hidden
    background url('../bg.png')
    .hd
        position absolute
        top 162px
        left 301px
        .title
            position absolute
            left 0
            top 0
            width 478px
            height 120px
            background url('./title.png') center center no-repeat
        .title-text
            position absolute
            left 46px
            top 147px
            width 403px
            height 102px
            background url('./title-text.png') center center no-repeat
    .qrcode-wrap
        position absolute
        top 518px
        left 40px
        .qrcode
            position absolute
            left 421px
            top 53px
            width 180px
            height 180px
            background url('./qrcode.png') center center no-repeat
        .text-wrap
            position absolute
            left 128px
            top 289px
            .text
                position absolute
                left 0px
                top 0px
                width 737px
                height 335px
                background url('./text.png') center center no-repeat
            .text1
                position absolute
                left 607px
                top -16px
                width 117px
                height 54px
                background url('./text1.png') center center no-repeat
            .text2
                position absolute
                left 174px
                top 84px
                width 117px
                height 54px
                background url('./text2.png') center center no-repeat
            .text3
                position absolute
                left 487px
                top 84px
                width 117px
                height 54px
                background url('./text3.png') center center no-repeat
            .text4
                position absolute
                left 440px
                top 186px
                width 237px
                height 54px
                background url('./text4.png') center center no-repeat
        .border
            position absolute
            left 0
            top 0
            width 1001px
            height 880px
            background url('./border.png') center center no-repeat
    .weixin-wrap
        position absolute
        bottom 0
        left 42px
        width 992px
        height 599px
        .weixin
            position absolute
            left 0
            top 0
            width 992px
            height 599px
            background url('./weixin.png') center center no-repeat
        .menu
            position absolute
            left 574px
            top 129px
            width 324px
            height 235px
            background url('./menu.png') center center no-repeat
        .click
            position absolute
            left 895px
            top 308px
            width 87px
            height 45px
            background url('./click.png') center center no-repeat
</style>

