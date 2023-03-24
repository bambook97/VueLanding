<template>
    <div :class="$style.container">
        <div :class="$style.ornament"></div>
        <div :class="$style.wrapper">
            <div :class="$style.text_block">
                <h2 :class="$style.title">Subscribe Newsletter</h2>
                <div :class="$style.descr">I will update good news and promotion service not spam</div>
            </div>

            <div :class="$style.form_container">
                <form action="submit-form.php" method="post">
                    <input type="text" id="email" name="email" required placeholder="Enter your email address..">
                    <button type="submit">Contact Now</button>
                </form>
            </div>
        </div>
        <div :class="$style.yellow_block"></div>
    </div>

</template>

<style lang="scss" module>
    .container  {
       margin-left: 120px;
       display: flex;
       flex-wrap: wrap;
       padding-bottom: 50px;
       min-height: 387px;
    }

    .ornament {
        position: absolute;
        margin-left: 1055px;
        width: 175px;
        height: 154px;
        background: url(../img/Newsletter/Dot.svg) center (center/cover) no-repeat;
        z-index: -1;
    }  

    .wrapper {
        align-self: center;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 1197px;
        height: 292px;
        background: url(../img/Newsletter/bg.svg) center (center/cover) no-repeat;
        z-index: 1;

        .text_block {
            margin-left: 92px;
            .title {
                font-family: 'Proxima Nova';
                font-style: normal;
                font-weight: 400;
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


        .form_container {
            margin-right: 98px;
            margin-left: 70px;
            position: relative;
            input {
            width: 238px;
            padding: 30px 200px 30px 30px;
            border-radius: 50px;
            border: none;
            box-shadow: 10px 20px 50px rgba(0, 0, 0, 0.15);
            white-space: normal;
            }
            button {
                position: absolute;
                width: 188px;
                height: 60px;
                background: #2639ED;
                border-radius: 60px;
                border: none;
                right: 9px;
                top: 8px;
                font-family: 'Proxima Nova';
                font-style: normal;
                font-weight: 400;
                font-size: 16px;
                line-height: 20px;
                color: #FFFFFF;
            }
        }
        
    }
    .yellow_block {
        position: absolute;
        left: 80px;
        top: 3582px;
        width: 178px;
        height: 178px;
        background: #FFF5DB;
        border-radius: 0px 100px 0px 100px;
        z-index: -1;
    }
</style>