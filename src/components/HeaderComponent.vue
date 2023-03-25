<template>
<header class="header">
    <div class="header__container">
        <div class="header__content">
            <div class="header__logo-img">
                <img src="@/assets/image/logo.jpg" alt="">
            </div>
            <ul class="header__menu">
                <li><a class="header__menu-links" href="">Продукты</a></li>
                <li><a class="header__menu-links" href="">Приложение</a></li>
                <li><a class="header__menu-links" href="">Дистрибуция</a></li>
                <li><a class="header__menu-links" href="">Где купить</a></li>
            </ul>
        </div>
    </div>
</header>
</template>

<script>

</script>

<style lang="scss">
.header{
    background: #fff;
    &__container{
        width: 1407px;
        height: 64px;
        margin: 0 auto;
        
    }
    &__content{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        height: 64px;
    }
    &__logo-img{
        display: flex;
        align-items: center;
    }
    &__menu{
        display: flex;
        justify-content: space-between;
        width: 690px;
        & li{
            list-style: none;
        }
        &-links{
            text-decoration: none;
            color: #000;
            font-size: 13px;
            line-height: 12px;
        }
    }
}
</style>