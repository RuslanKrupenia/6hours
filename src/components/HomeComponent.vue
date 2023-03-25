<template>
<section class="home">
    <div class="home__container">
        <div class="home__content">
            <div class="home__logo-img">
                <img src="@/assets/image/header-logo.png" alt="">
            </div>
            <div class="home__title">Новый стандарт
                одноразовых е-сигарет.</div>
            <div class="home__buttons">
                <button class="home__more">Подробнее <span>></span></button>
                <button class="home__buy">Где купить</button>
            </div>
        </div>
    </div>
</section>

</template>

<script>


</script>


<style lang="scss">
.home{
    background-image: url(@/assets/image/header-bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top center;
    
    &__container{
        margin: 0 auto;
        min-height: 100vh;
        height: 100%;
        width: 937px;
        display: flex;
        justify-content: left;
        align-items: center;

        
    }
    &__content{
        width: 456px;
        height: 312px;
    }
    &__logo-img{
        width: 388px;
        height: 78px;
        position: relative;
        right: 50px;
        margin-bottom: 35px;
    }
    &__title{
        width: 400px;
        height: 88px;
        font-size: 32px;
        line-height: 44px;
        color: #fff;
        margin-bottom: 76px;
    }
    &__buttons{
        width: 388px;
        height: 48px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    &__more{
        background: none;
        color: #fff;
        width: 120px;
        height: 20px;
        display: flex;
        cursor: pointer;
        border: none;
        & span{
            margin-left: 15px;
        }
    }
    &__buy{
        border: 1px solid #FFFFFF;
        border-radius: 100px;
        width: 208px;
        height: 48px;
        background: none;
        color: #fff;
        cursor: pointer;
    }
}

</style>