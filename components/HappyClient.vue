<template>

    <div :class="$style.container">

        <div :class="$style.text_block">
            <div :class="$style.title">What our happy client say</div>
            <div :class="$style.descr">Several selected clients, who already believe in our service.</div>

        </div>
        
        <div :class="$style.slider_block">

            <div :class="$style.slider">
                <div :class="$style.slider_img"></div>
                <div :class="$style.pink_circle"></div>
                <div :class="$style.ornament"></div>
                <div :class="$style.descr_block">
                    <div :class="$style.slider_title">Matthew Paul</div>
                    <div :class="$style.slider_descr">Perfect, very good job! Thank you for the amazing design and work. Really impressed with the high quality and quick turnaround time. Highly recommend.</div>
                    <ul :class="$style.slider_pointers">
                        <li :class="$style.pointer">
                            <div></div>
                        </li>
                        <li :class="$style.pointer">
                            <div></div>
                        </li>
                        <li :class="$style.pointer">
                            <div></div>
                        </li>
                        <li :class="$style.pointer">
                            <div></div>
                        </li>
                        <li :class="$style.pointer">
                            <div></div>
                        </li>
                    </ul>
                </div>
            </div>

            <img :class="$style.group_img" src="../img/HappyClient/Group.png" alt="">
            <div :class="$style.yellow_ellipse"></div>

        </div>
    </div>

</template>

<style lang="scss" module>

    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 120px 69px 92px 107px;
        margin-top: 50px;
    }
    
    .text_block {
        .title {
            font-family: 'Proxima Nova';
            font-style: normal;
            font-weight: 700;
            font-size: 40px;
            line-height: 60px;
            text-align: center;
        }
        .descr {
            font-family: 'Averta Demo PE Cutted Demo';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 160%;
            text-align: center;
            color: #757575;
        }
    }
    .slider_block {
        display: flex;
        flex-direction: row;
        align-items: center;

        .slider {
            margin-top: 110px;
            margin-left: 10px;
            display: flex;
            flex-direction: row;
            align-items: center;
            .slider_img {
                width: 389px;
                height: 389px;
                border-radius: 500px 0px 500px 500px;
                background: url(../img/HappyClient/hero.png) center (center/cover) no-repeat;
            }
            .pink_circle{
                position: absolute;
                margin-top: 300px;
                width: 120px;
                height: 120px;
                border: 8.8px solid #FF007A;
                border-radius: 100%;
                z-index: -1;
            }
            .ornament{
                position: absolute;
                margin-bottom: 310px;
                margin-left: 230px;
                background: url(../img/HappyClient/Dot.png) center (center/cover) no-repeat;
                width: 196px;
                height: 154px;
                z-index: -1;
            }
            .descr_block {
                width: 412px;
                height: 185px;
                margin-left: 67px;
                margin-right: 38px;
                .slider_title {
                    font-family: 'Proxima Nova';
                    font-style: normal;
                    font-weight: 700;
                    font-size: 24px;
                    line-height: 30px;
                    text-align: left;
                    color: #000000;
                }
                .slider_descr {
                    margin-top: 21px;
                    font-family: 'Averta Demo PE Cutted Demo';
                    font-style: normal;
                    font-weight: 400;
                    font-size: 16px;
                    line-height: 160%;
                    color: #565656;
                }
                .slider_pointers {
                    margin-top: 40px;
                    display: flex;
                    flex-direction: row;
                    .pointer {
                        list-style-type: none;
                        margin-right: 26px;
                        cursor: pointer;
                        :hover {
                            box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);;
                        }
                        div {
                            width: 16px;
                            height: 16px;
                            border-radius: 100%;
                            border: none;
                            background: #E7F0FC;
                        }
                    }
                }
            }
        }  
        .group_img {
            margin-top: 150px;
            width: 348px;
            height: 355px;
        }
        .yellow_ellipse {
            position: absolute;
            margin-left: 940px;
            margin-top: 205px;
            width: 184px;
            height: 184px;
            background: #FFF5DB;
            border: none;
            border-radius: 100%;
            z-index: -1;
        }
    }

</style>
