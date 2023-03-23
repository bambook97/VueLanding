<template>
    <div :class="$style.container">

        <div :class="$style.text_block">

            <div :class="$style.title">How can we help your Business ?</div>

            <div :class="$style.descr">We build readymade websites, mobile applications, and elaborate online business
                services.</div>
        </div>

        <div :class="$style.orange_ellipse">
                <img src="../img/help/OrangeRect.svg" alt="">
        </div>

        <div :class="$style.img_block">
            <ul class="$style.firstColumn">
                <li>
                    <div :class="$style.help_block">
                        <div :class="[$style.img_container, $style.blue_icon]">
                            <img src="../img/help/box-search.svg" alt="">
                        </div>
                        <div :class="$style.title">Business Idea <br> Planning</div>
                        <div :class="$style.descr">We present you a proposal and <br> discuss niffty-gritty like</div>
                    </div>
                </li>
                <li>
                    <div :class="$style.help_block">
                        <div :class="[$style.img_container, $style.pink_icon]">
                            <img src="../img/help/code.svg" alt="">
                        </div>
                        <div :class="$style.title">Development <br> Website and App</div>
                        <div :class="$style.descr">Communication protocols apart <br> from engagement models</div>
                    </div>
                </li>
            </ul>

            <ul :class="$style.secondColumn">
                <li>
                    <div :class="$style.help_block">
                        <div :class="[$style.img_container, $style.yellow_icon]">
                            <img src="../img/help/empty-wallet.svg" alt="">
                        </div>
                        <div :class="$style.title">Financial <br> Planning System</div>
                        <div :class="$style.descr">Protocols apart from aengage <br> models, pricing billing</div>
                    </div>
                </li>
                <li>
                    <div :class="$style.help_block">
                        <div :class="[$style.img_container, $style.green_icon]">
                            <img src="../img/help/chart-square.svg" alt="">
                        </div>
                        <div :class="$style.title">Market Analysis <br> Project</div>
                        <div :class="$style.descr">Protocols apart from aengage <br> models, pricing billing</div>
                    </div>
                </li>
            </ul>
        </div>

        <div :class="$style.blue_ellipse">
        <img src="../img/help/BlueRect.svg" alt="">
        </div>
        
        <div :class="$style.pink_ring">
            <img src="../img/help/PinkRIng.svg" alt="">
        </div>

        <div :class="$style.ornament">
            <img src="../img/help/ornament.png" alt="">
        </div>

    </div>
</template>

<style lang="scss" module>
.container {
    margin-left: 90px;
    min-width: 1350px;
    display: flex;
    flex-direction: row;
    align-items: center;

}

.text_block {
    display: flex;
    flex-direction: column;
    .title {
        font-family: 'Proxima Nova';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 49px;
        color: #000000;

    }

    .descr {
        margin-top: 17px;
        font-family: 'Averta Demo PE Cutted Demo';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 160%;
        color: #757575;

    }
}
.orange_ellipse {
        position: absolute;
        width: 178px;
        height: 178px;
        left: 50px;
        top: 1385px;
        z-index: -1;
}

.blue_ellipse {
    position: absolute;
    left: 393px;
    top: 1200px;
    z-index: -1;
}

.pink_ring {
    position: absolute;
    left: 1177px;
    top: 1780px;
    z-index: -2;
}

.ornament {
    position: absolute;
    left: 125px;
    top: 1700px;
    z-index: -2;
}


.img_block {
    margin-left: 90px;
    margin-right: 180px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    .firstColumn {
        margin-bottom: 0;
    }

    .secondColumn {
        margin-bottom: 70px;
    }

    ul {
        display: flex;
        flex-direction: column;

        li {
            list-style-type: none;
        }
    }

    .help_block {
        width: 308px;
        height: 379px;
        background: #FFFFFF;
        border: 1px solid #F2F2F2;
        box-shadow: 0px 10px 50px rgba(0, 0, 0, 0.05);
        border-radius: 40px;
        margin-bottom: 30px;
        margin-right: 35px;

        .title {
            margin-top: 30px;
            font-family: 'Averta Demo PE Cutted Demo';
            font-style: normal;
            font-weight: 400;
            font-size: 24px;
            line-height: 30px;
            text-align: center;

            color: #000000;
        }

        .descr {
            margin-top: 27px;
            margin-bottom: 57px;
            font-family: 'Averta Demo PE Cutted Demo';
            font-style: normal;
            font-weight: 400;
            font-size: 16px;
            line-height: 140%;
            text-align: center;
            color: #757575;
        }

        .img_container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 39px;
            margin-left: 94px;
            height: 121px;
            width: 121px;
            border-radius: 20px;

            

            img {
                width: 66px;
                height: 66px;

                .blueIcon {
                    background: #F1F7FF;
                    border-radius: 20px;
                }
            }
        }

        .blue_icon {
                background: #F1F7FF;
            }
        .pink_icon {
            background: #FFF2F8;
        }

        .yellow_icon {
            background: #FFF7E3;
        }
        .green_icon {
            background: #DEFFEE;
        }
    }
}</style>