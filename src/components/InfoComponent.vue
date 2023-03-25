<template>
<section class="info">
    <div class="info__container">
        <div class="info__content">
            <div class="info__sig">
                <div class="info__text">
                    <div class="info__title">Об электронных сигаретах</div>
                    <div class="info__subtitle">Plonq — электронный испаритель, который преобразует жидкость в пар.</div>
                    <button class="info__more"> Подробнее <span>></span></button>
                </div>
                <div class="info__sig-image">
                    <img src="@/assets/image/sigarette.png" alt="">
                </div>
            </div>
            <div class="info__app">
                <div class="info__text">
                    <div class="info__title">О приложении</div>
                    <div class="info__subtitle">Plonq AI создан на основе поведенческой терапии, которая доказала свою эффективность.</div>
                    <button class="info__more"> Подробнее <span>></span></button>
                </div>
                <div class="info__app-image">
                    <img src="@/assets/image/phone.png" alt="">
                </div>
            </div>
        </div>
    </div>
</section>

</template>

<script>

</script>

<style lang="scss">
.info{
    background: #fff;
    &__container{
        width: 1408px;
        min-height: 100vh;
        height: 100%;
        margin: 0 auto;
    }
    &__content{
        width: 100%;
        height: 465px;
        display: flex;
        justify-content: space-between;
    }
    &__sig{
        width: 688px;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #F9F9F9;
    }
    &__title{
        font-family: 'Gotham Pro Bold';
        width: 200px;
        height: 56px;
        font-size: 15px;
        line-height: 21px;
        margin-bottom: 28px;
    }
    &__subtitle{
        width: 328px;
        height: 42px;
        font-size: 15px;
        line-height: 21px;
        margin-bottom: 53px;
    }
    &__more{
        font-family: 'Gotham Pro Bold';
        background: none;
        cursor: pointer;
        border: none;
        & span{
            margin-left: 15px;
        }
    }
    &__sig-image{
        margin-top: auto;
    }
    &__app{
        width: 688px;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #F9F9F9;
    }
}
</style>