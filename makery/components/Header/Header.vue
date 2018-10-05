<template>
<div>
    <nav id='header' :class="pagesize">
        <img src="~/static/img/Makery Logo.png" alt="">
        <hr>
        <ul class="main-menu">
            <li>
                <nuxt-link to="/">MAKERY</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/item-list">디자인 하러가기</nuxt-link>
                <ul class="sub-menu">
                    <li>포스터</li>
                    <li>배너</li>
                </ul>
            </li>
            <li>
                <nuxt-link to="/contact">고객 센터</nuxt-link>
            </li>
        </ul>
    </nav>
</div>
</template>

<script scoped>
export default {
    props:['width'],
    computed:{
        pagesize(){
            return this.width>1024?'page-lg':'page-sm'
        }
    },

}
</script>

<style scoped>
.page-lg{
    position: fixed;
    width:270px;
    z-index: 100;
}
.page-sm{
    position: fixed;
    z-index: 100;
    width: 100%;
    height: 70px;
    display: in;
}

img{
    width: 250px;

}


.page-lg li{
    display: list-item;
    font-size: 1.2em;
    list-style-type: none;
}

.page-sm ul{
    display: none;
}

.page-sm li{
    display: inline-block;
}

.main-menu li:hover .sub-menu{
    display: block;
}
.sub-menu{
    display: none;
}

</style>
