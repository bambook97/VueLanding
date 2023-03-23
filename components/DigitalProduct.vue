<template>
<div :class="$style.container">

    <div :class="$style.text_block">
        <div :class="$style.title">A Digital Product Agency</div>
        <div :class="$style.descr">Leading digital agency with solid design and development <br> expertise. We build readymade websites, mobile applications,<br> and elaborate online business services.</div>
        <button :class="$style.contact">Contact Now</button>
    </div>

    <div :class="$style.img_block">
        <div :class="$style.blueEllipse"></div>
        <div :class="$style.conf"></div>
        <div :class="$style.orangeRectangle"></div>
    </div>

    <div :class="$style.dotOrnament"></div>

</div>
</template>

<style lang="scss" module>

.container {
    margin-top: 40px;
    margin-left: 120px;
    display: flex;
    flex-direction: row;
}

.text_block {
    width: 600px;
    font-family: 'Averta Demo PE Cutted Demo';
    font-style: normal;
    font-weight: 400;
    .title {
        margin-top: 123px;
        font-size: 40px;
        line-height: 49px;
        color: #000000;
    }
    .descr {
        margin-top: 40px;
        font-size: 16px;
        line-height: 160%;
        color: #565656;
    }
    button {
        margin-top: 33px;
        width: 215px;
        height: 65px;
        background: #2639ED;
        border-radius: 60px;
        border: none;
        font-size: 20px;
        line-height: 25px;
        color: #FFFFFF;
    }
}

.dotOrnament {
    position: absolute;
    width: 404px;
    height: 154px;
    left: 68px;
    top: 469px;
    background: url(../img/DotOrnament.svg);
    z-index: -1;
}              

.img_block {
    margin-left: 95px;
    width: 750px;
    .blueEllipse {
        position: absolute;
        width: 129px;
        height: 129px;
        left: 623px;
        top: 115px;
        z-index: -1;
        background: #DAE9FF;
        border-radius: 50%;
    }

    .conf  {
        position: absolute;
        width: 754px;
        height: 512px;
        left: 686px;
        top: 116px;
        background: url(../img/conf.svg);
        border-radius: 0px 0px 0px 200px;
    }
    .orangeRectangle{
        position: absolute;
        width: 178px;
        height: 178px;
        left: 1142px;
        top: 546px;
        background: #FFF5DB;
        border-radius: 0px 0px 100px 0px; 
        z-index: -1;
    }
}

</style>