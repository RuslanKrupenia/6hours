<template>
<section class="product">
    <div class="product__container">
        <div class="product__content">
            <div class="product__item">
                <div class="product__img">
                    <img src="@/assets/image/plonq-1.png" alt="">
                </div>
                <div class="product__text">
                    <div class="product__logo">
                        <img src="@/assets/image/plonq-400.png" alt="">
                    </div>
                    <div class="product__title">Одноразовое устройство Plonq на 400 затяжек</div>
                    <div class="product__price">370 ₽</div>
                    <button class="product__buy">Где купить</button>
                </div>
            </div>
            <div class="product__item">
                <div class="product__img">
                    <img src="@/assets/image/plonq-2.png" alt="">
                </div>
                <div class="product__text">
                    <div class="product__logo">
                        <img src="@/assets/image/plonq-500.png" alt="">
                    </div>
                    <div class="product__title">Одноразовое устройство Plonq на 500 затяжек</div>
                    <div class="product__price">430 ₽</div>
                    <button class="product__buy">Где купить</button>
                </div>
            </div>
            <div class="product__item">
                <div class="product__img">
                    <img src="@/assets/image/plonq-3.png" alt="">
                </div>
                <div class="product__text">
                    <div class="product__logo">
                        <img src="@/assets/image/plonq_X.png" alt="">
                    </div>
                    <div class="product__title">Стартовый набор Plonq X</div>
                    <div class="product__wait">Скоро в продаже</div>
                </div>
            </div>
            <div class="product__item">
                <div class="product__img">
                    <img src="@/assets/image/plonq-4.png" alt="">
                </div>
                <div class="product__text">
                    <div class="product__logo">
                        <img src="@/assets/image/plonq_X.png" alt="">
                    </div>
                    <div class="product__title">Два сменных картриджа для устройства Plonq X</div>
                    <div class="product__wait">Скоро в продаже</div>
                </div>
            </div>
        </div>
    </div>
</section>

</template>

<script>


</script>

<style lang="scss">
.product{
    background: #fff;
    &__container{
        width: 1136px;
        min-height: 100vh;
        height: 100%;
        margin: 0 auto;
        display: flex;
        align-items: center;
    }
    &__content{
        width: 100%;
        height: 1135px;
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
    }
    &__item{
        width: 416px;
        height: 450px;
        display: flex;
        align-items: center;
        

        
    }
    &__item:first-of-type{
        margin-right: auto;
    }
    &__item:last-of-type{
        margin-left: auto;
    }
    &__logo{
        margin-bottom: 55px;
    }
    &__text{
        width: 220px;
        height: 280px;
        
        
    }
    &__title{
        width: 208px;
        height: 42px;
        margin-bottom: 20px;
        font-size: 15px;
        line-height: 21px;
    }
    &__price{
        font-family: 'Gotham Pro Bold';
        font-size: 21px;
        line-height: 30px;
        margin-bottom: 43px;
    }
    &__buy{
        width: 208px;
        height: 48px;
        background: none;
        border-radius: 100px;
        border: 1px solid #000;
        cursor: pointer;
    }
    &__wait{
        color: #C8BB93;
        font-size: 15px;
        line-height: 21px;
    }
}

</style>