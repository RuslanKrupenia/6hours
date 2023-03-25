<template>
<section class="map">
    <div class="map__container">
        <div class="map__content">
            <div class="map__image">
                <img src="@/assets/image/map.png" alt="">
            </div>
            <div class="map__title">Найдите Plonq 
                среди <span>4244</span> магазинов</div>
            <button class="map__button">Найти магазин</button>
        </div>
    </div>
</section>

</template>

<script>

</script>

<style lang="scss">
.map{
    background-color: #fff;
    &__container{
        width: 1409px;
        min-height: 100vh;
        margin: 0 auto;
        height: 100%;
        align-items: center;
    }
    &__content{
        background-color: #F9F9F9;
        height: 690px;
        justify-content: space-between;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-evenly;
    }
    &__image{
        margin-bottom: 35px;
    }
    &__title{
        margin: 0 auto;
        text-align: center;
        align-items: center;
        font-size: 22px;
        line-height: 32px;
        width: 270px;
        height: 64px;
        margin-bottom: 36px;
        & span{
            font-family: 'Gotham Pro Bold';
        }
    }
    &__button{
        width: 208px;
        height: 48px;
        background: none;
        border: 1px solid #000;
        border-radius: 100px;
        margin: 0 auto;
        cursor: pointer;
        margin-bottom: 50px;
    }
}
</style>