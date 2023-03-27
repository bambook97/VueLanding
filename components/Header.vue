<template>
    <div :class="$style.container">

        <div :class="$style.logo">

            <a href="">
                <span>a+</span> Studio
            </a>
            
        </div>

        <nav :class="$style.navbar">
            <ul>
                <li><a href="">Home</a>
                </li>
                <li><a href="">What We Do</a>
                </li>
                <li><a href="">Service</a>
                </li>
                <li><a href="">Project</a>
                </li>
                <li><a href="">Blog</a>
                </li>
                <li><a href="">Contact</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<style lang="scss" module>


.container {
    margin: 42px 120px 0 120px ;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.logo {
    a {
        text-decoration: none;
        font-family: 'Averta Demo PE Cutted Demo';
        font-style: normal;
        font-weight: 400;
        font-size: 27px;
        line-height: 20px;
        color: #000000;
        margin-left: 39px;
    }
    span {
        font-family: 'Proxima Nova';
        font-style: normal;
        font-weight: 700;
        text-transform: uppercase;
        line-height: 33px;
    }
}
.navbar {
    margin-left: 435px;

    ul {
        display: flex;
        flex-direction: row;
    }
    li {
        list-style-type: none;
        margin-left: 60px;
        :first-child {
            margin-left: 0;
        }
    } 
    a {
    text-decoration: none;
    font-family: 'Averta Demo PE Cutted Demo';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 20px;
    color: #000000;
    }
}

</style>