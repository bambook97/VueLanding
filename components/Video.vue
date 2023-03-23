<template>

<div :class="$style.container">

    <div :class="$style.video_box_container">
        <button></button>
    </div>

    <div :class="$style.text_block">
        <div :class="$style.title">Great Digital Product Agency since 2016 </div>
        <div :class="$style.descr">Our Business Plan is a written document describing a company's core business activites, Objectives, and how it plans to achieve its goals. Our goal is to provide our client high quality Product with modern idea accordingly their budgets and according thir reuirements.</div>
    </div>

    <div :class="$style.blue_ellipse">
        <img src="../img/video/blue.svg" alt="">
    </div>

    <div :class="$style.orange_ellipse">
        <img src="../img/video/orange.svg" alt="">
    </div>

</div>

</template>

<style lang="scss" module>

.container {
    padding: 146px 120px 0 120px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.video_box_container{
display: flex;
align-items: center;
justify-content: center;
min-width: 550px;
min-height: 432px;
box-shadow: 10px 20px 50px rgba(0, 0, 0, 0.15);
border-radius: 32px;
background: url(../img/video/VID.png) center (center/cover) no-repeat;
button {
    background-image: url(../img/video/playButton.svg);
    width: 78px;
    height: 78px;
    border-radius: 100%;
    border: none;
    cursor: pointer;
}
}
.text_block {
    margin-left: 118px;
    width: 530px;
    .title {
        margin-top: 80px;
        margin-right: 63px;
        font-family: 'Proxima Nova';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 49px;
        color: #000000;
    }
    .descr {
        margin-top: 15px;
        font-family: 'Averta Demo PE Cutted Demo';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 160%;
        color: #565656;
    }

}
.blue_ellipse {
    position: absolute;
    left: 750px;
    top: 2225px;
    z-index: -2;
    }
.orange_ellipse {
    position: absolute;
    left: 582px;
    top: 2500px;
    z-index: -2;
}
</style>