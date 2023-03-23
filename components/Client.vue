<template>

<div :class="$style.container">

    <div :class="$style.text_block">

        <div :class="$style.title">Our Client</div>
        <div :class="$style.descr">Several selected clients, who already believe <br> in our service.</div>

    </div>

    <div :class="$style.link_block">
        <ul>
            <li>
            <a href="">
                <img src="../img/OurClient/GoogleLogo.svg" alt="">
            </a>
        </li>

        <li>
            <a href="">
                <img src="../img/OurClient/AirbnbLogo.svg" alt="">
            </a>
        </li>

        <li>
            <a href="">
                <img src="../img/OurClient/UberEatsLogo.svg" alt="">
            </a>
        </li>
        
        <li>
            <a href="">
                <img src="../img/OurClient/AmazonLogo.svg" alt="">   
            </a></li>
        </ul>

    </div>

</div>



</template>

<style lang="scss" module>

.container {
    min-height: 170px;
    min-width: 1200px;
    padding-top: 40px;
    margin: 40px 120px 90px 120px;
    display: flex;
    flex-direction: row;
    
}

.text_block {
    display: flex;
    flex-direction: column;
    
    
    .title{
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

.link_block {
    margin-top: 40px;
    margin-left: 64px;
    ul{
        margin-top: 22px;
        display: flex;
        flex-direction: row;
        align-items: center;  
        li {
            list-style-type: none;
            margin-right: 60px;
            &:last-child {
                margin-bottom: -20px;
                margin-right: 0px;
                img {
                    width: 140px;
                    height: 40px;
                }
        }
        img {
            height: 50px;
            width: 150px;
        }
        }
    }
    
}

</style>