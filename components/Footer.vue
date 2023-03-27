<template>
    <footer>
        <div :class="$style.pointer_line"></div>
        <div :class="$style.container">
        
            <div :class="$style.logo_block">

                <h2 :class="$style.logo"><span>a+</span> Studio</h2>
                <div :class="$style.descr">Leading digital agency with solid design <br> and development expertise. We build <br> readymade websites, mobile applications, <br> and elaborate online business services.</div>
                <div :class="$style.social_block">
                
                    <a href="#">
                        <img src="../img/Footer/facebook.svg" alt="">
                    </a>
                    <a href="#">
                        <img src="../img/Footer/twitter.svg" alt="">
                    </a>
                    <a href="#">
                        <img src="../img/Footer/linkedin.svg" alt="">
                    </a>
                </div>

            </div>

            <div :class="$style.text_block">
                <h2 :class="$style.title">What We Do</h2>
                <ul>
                    <li><a href="">Web Design</a></li>
                    <li><a href="">App Design</a></li>
                    <li><a href="">Social Media Manage</a></li>
                    <li><a href="">Market Analysis Project</a></li>
                </ul>
            </div>

            <div :class="$style.text_block">
                <h2 :class="$style.title">Company</h2>
                <ul>
                    <li><a href="">About Us</a></li>
                    <li><a href="">Career</a></li>
                    <li><a href="">Become Investor</a></li>
                </ul>
            </div>

            <div :class="$style.text_block">
                <h2 :class="$style.title">Support</h2>
                <ul>
                    <li><a href="">FAQ</a></li>
                    <li><a href="">Policy</a></li>
                    <li><a href="">Business</a></li>
                </ul>
            </div>

            <div :class="[$style.text_block, $style.text_block_contact]">
                <h2 :class="$style.title">Contact</h2>
                <ul>
                    <li><a href="">WhatsApp</a></li>
                    <li><a href="">Support 24</a></li>
                </ul>
            </div>

        </div>
        <div :class="$style.pointer_line"></div>
    </footer>
    
</template>

<style lang="scss" module>


footer {
    padding: 110px 107px 64px 108px;

    .pointer_line {
        border: 1px solid #E4E4E4;
    }
    .container {
        margin-top: 60px;
        margin-bottom: 29px;
        display: flex;
        flex-direction: row;
        justify-content: center;

    .logo_block {
        margin-right: 190px;
        h2 {
            text-decoration: none;
            font-family: 'Averta Demo PE Cutted Demo';
            font-style: normal;
            font-weight: 400;
            font-size: 27px;
            line-height: 20px;
            color: #000000;
            span {
                font-family: 'Proxima Nova';
                font-style: normal;
                font-weight: 700;
                text-transform: uppercase;
                line-height: 33px;
            }
        }
        .descr {
            margin-top: 26px;
            font-family: 'Averta Demo PE Cutted Demo';
            font-style: normal;
            font-weight: 400;
            font-size: 14px;
            line-height: 160%;
            color: #565656;
        }
        .social_block {
            margin-top: 40px;
            a {
                margin-right: 16px;
            }
        }
    }
    .text_block {
            margin-right: 120px;
            &_contact {
                margin-right: 0;
            }
            .title {
                font-family: 'Averta Demo PE Cutted Demo';
                font-style: normal;
                font-weight: 400;
                font-size: 20px;
                line-height: 25px;
                color: #000000;
            }
            ul {
                margin-top: 24px;
                line-height: 30px;
                li {
                    list-style-type: none;
                    a {
                        text-decoration: none;
                        font-family: 'Averta Demo PE Cutted Demo';
                        font-style: normal;
                        font-weight: 400;
                        font-size: 14px;
                        line-height: 200%;
                        color: #000000;
                    }
                }
            }
        }
}
}



</style>