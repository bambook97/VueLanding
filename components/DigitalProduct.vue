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
    min-width: 1380px;
    min-height: 610px;
    margin-top: 40px;
    margin-left: 120px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.text_block {
    margin-left: 180px;
    width: 600px;
    font-family: 'Proxima Nova';
    font-style: normal;
    font-weight: 700;
    .title {
        margin-top: 123px;
        font-size: 40px;
        line-height: 49px;
        color: #000000;
    }
    .descr {
        font-family: 'Averta Demo PE Cutted Demo';
        font-weight: 400;
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
        cursor: pointer;
    }
}

.dotOrnament {
    margin-top: 350px;
    margin-left: 38px;
    position: absolute;
    width: 404px;
    height: 154px;
    background: url(../img/Product/DotOrnament.svg);
    z-index: -1;
}              

.img_block {
    margin-left: 95px;
    width: 750px;
    min-height: 650px;
    min-width: 820px;
    .blueEllipse {
        margin-left: 60px;
        position: absolute;
        width: 129px;
        height: 129px;
        z-index: -1;
        background: #DAE9FF;
        border-radius: 50%;
    }

    .conf  {
        position: absolute;
        width: 754px;
        height: 512px;
        margin-left: 120px;
        background: url(../img/Product/Conf.png) center (center/cover) no-repeat;
        border-radius: 0px 0px 0px 200px;
        border: 1px solid #000000;
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        overflow-x: hidden;
    }
    .orangeRectangle{
        position: absolute;
        margin-top: 430px;
        margin-left: 450px;
        width: 178px;
        height: 178px;
        background: #FFF5DB;
        border-radius: 0px 0px 100px 0px; 
        z-index: -1;
    }
}

</style>