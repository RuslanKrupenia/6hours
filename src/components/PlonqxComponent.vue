<template>
<section class="plonqx">
    <div class="plonqx__container">
        <div class="plonqx__content">
            <div class="plonqx__text">
                <div class="plonqx__logo">
                    <img src="@/assets/image/plonq_X.png" alt="">
                </div>
                <div class="plonqx__title">Электронная сигарета, которая умеет удивлять.</div>
                <div class="plonqx__buttons">
                    <button class="plonqx__more">Подробнее <span>></span></button>
                    <div class="plonqx__wait">Скоро в продаже</div>
                </div>
            </div>
            <div class="plonqx__phone-img">
                <img src="@/assets/image/Plonq-x.png" alt="">
            </div>
        </div>
    </div>
</section>
</template>

<script>

</script>

<style lang="scss">
.plonqx{
    background: #fff;
    &__container{
        width: 937px;
        min-height: 100vh;
        height: 100%;
        margin: 0 auto;
        display: flex;
        align-items: center;
    }
    &__content{
        height: 1000px;
        display: flex;
        align-items: center;
    }
    &__text{
        width: 408px;
        height: 300px;
    }
    &__logo{
        margin-bottom: 61px;
        width: 280px;
        height: 61px;
    }
    &__title{
        font-size: 32px;
        line-height: 44px;
        color: #000;
        margin-bottom: 68px;
    }
    &__buttons{
        display: flex;
        justify-content: space-between;
        width: 350px;
        height: 21px;
    }
    &__more{
        width: 106px;
        height: 21px;
        background: none;
        border: none;
        display: flex;
        & span{
            margin-left: 15px;
        }
    }
    &__wait{
        color: #C8BB93;
    }
    &__phone-img{
        width: 480px;
        height: 750px;
        display: flex;
        align-items:end;
    }

}
</style>