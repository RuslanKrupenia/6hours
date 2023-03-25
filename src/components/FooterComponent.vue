<template>
<footer class="footer">
    <div class="footer__container">
        <div class="footer__content">
            <div class="footer__up">
                <div class="footer__logo">
                    <img src="@/assets/image/logo.jpg" alt="">
                </div>
                <div class="footer__sub">
                    <div class="footer__sub-text">Подпишитесь на наши обновления</div>
                    <div class="footer__subscribe">
                        <input type="text" class="footer__input">
                        <button class="footer__subscribe-btn">Подписаться</button>
                    </div>
                </div>
                <div class="footer__language-swicher"><a class="footer__language-swicher-RU" href="">RU</a>|<a class="footer__language-swicher-EN" href="">EN</a></div>
            </div>
            <div class="footer__down">
                <div class="footer__apps">
                    <div class="footer__apps-IOS">
                        <div class="footer__apps-IOS-img">
                            <img src="@/assets/image/Apple_icon.png" alt="">
                        </div>
                        <div class="footer__apps-IOS-text">
                            <div class="footer__apps-IOS-title">Coming soon</div>
                            <div class="footer__apps-IOS-subtitle">for IOS</div>
                        </div>
                    </div>
                    <div class="footer__apps-android">
                        <div class="footer__apps-android-img">
                            <img src="@/assets/image/Android_icon.png" alt="">
                        </div>
                        <div class="footer__apps-android-text">
                            <div class="footer__apps-android-title">Coming soon</div>
                            <div class="footer__apps-android-subtitle">for IOS</div>
                        </div>
                    </div>
                </div>
                <div class="footer__links">
                    <div class="footer__links-item">
                        <ul class="footer__links-list">
                            <div class="footer__links-title">Продукты</div>
                            <li><a class="footer__links-link" href="">Plonq 400</a></li>
                            <li><a class="footer__links-link" href="">Plonq 500</a></li>
                            <li><a class="footer__links-link" href="">Plonq X</a></li>
                        </ul>
                    </div>
                    <div class="footer__links-item">
                        <ul class="footer__links-list">
                            <div class="footer__links-title">Технологии</div>
                            <li><a class="footer__links-link" href="">О приложении</a></li>
                            <li><a class="footer__links-link" href="">Об электронных сигаретах</a></li>
                        </ul>
                    </div>
                    <div class="footer__links-item">
                        <ul class="footer__links-list">
                            <div class="footer__links-title">Поддержка</div>
                            <li><a class="footer__links-link" href="">Связаться с нами</a></li>
                            <li><a class="footer__links-link" href="">Условия возврата</a></li>
                            <li><a class="footer__links-link" href="">Политика конфиденциальности</a></li>
                        </ul>
                    </div>
                    <div class="footer__links-item">
                        <ul class="footer__links-list">
                            <div class="footer__links-title">Прочее</div>
                            <li><a class="footer__links-link" href="">Точки продаж</a></li>
                            <li><a class="footer__links-link" href="">О Компании</a></li>
                            <li><a class="footer__links-link" href="">Оптовым покупателям</a></li>
                        </ul>
                    </div>
                </div>
                <div class="footer__inst">
                    <div class="footer__inst-img">
                        <a href=""><img src="@/assets/image/Instagram_icon.svg" alt=""></a>
                    </div>
                    <div class="footer__inst-text">© 2021 PLONQ LLC <br>
                        40900 Woodward Avenue Suite <br>
                        111 Bloomfield Hills <br>
                        MI 48304 USA</div>
                </div>
            </div>
            <div class="footer__text-sell">ПРОДАЖА НЕСОВЕРШЕННОЛЕТНИМ ЗАПРЕЩЕНА. <br>
                Сайт используется исключительно в целях информирования действующих потребителей продукции PLONQ <br>
                Защищено выпущенными и/или находящимися на одобрении международными патентами.. </div>
        </div>
    </div>
</footer>

</template>

<script>

</script>

<style lang="scss">
.footer{
    background-color: #fff;
    &__container{
        width: 1408px;
        margin: 0 auto;
    }
    &__content{
        height: 450px;
        width: 100%;
    }
    &__up{
        display: flex;
        justify-content: space-between;
        margin-bottom: 45px;
        width: 100%;
        height: 86px;
    }
    &__logo{
        width: 88px;
        height: 19px;
    }
    &__sub{
        width: 600px;
        height: 85px;
        &-text{
            font-size: 14px;
            line-height: 21px;
            margin-bottom: 30px;
        }
    }
    &__subscribe{
        width: 600px;
        height: 40px;
        display: flex;
        justify-content: space-between;
    }
    &__input{
        width: 425px;
        height: 40px;
        background-color: #F9F9F9;
        border: none;
    }
    &__subscribe-btn{
        width: 152px;
        height: 40px;
        color: #fff;
        background-color: #000;
        border-radius: 4px;
    }
    &__language-swicher{
        width: 58px;
        height: 20px;
        &-RU {
            color: #C8BB93;
            text-decoration: none;
        }
        &-EN {
            color: #000;
            text-decoration: none;
        }
    }
    &__down{
        width: 100%;
        height: 185px;
        display: flex;
        justify-content: space-between;
        margin-bottom: 87px;
    }
    &__apps{
        width: 152px;
        height: 129px;
        &-IOS{
            display: flex;
            justify-content: space-between;
            margin-bottom: 29px;
            &-img{
                width: 28px;
                height: 33px;
                display: flex;
                align-items: center;
                margin-right: 17px;
            }
            &-text{
                width: 107px;
                height: 50px;
            }
            &-title{
                font-family: 'Gotham Pro Bold';
                font-size: 14px;
                line-height: 21px;
            }
            &-subtitle{
                color: #AAAAAA;
            }
        }
        &-android{
            display: flex;
            justify-content: space-between;
            margin-bottom: 29px;
            &-img{
                width: 28px;
                height: 33px;
                display: flex;
                align-items: center;
                margin-right: 17px;
            }
            &-text{
                width: 107px;
                height: 50px;
            }
            &-title{
                font-family: 'Gotham Pro Bold';
                font-size: 14px;
                line-height: 21px;
            }
            &-subtitle{
                color: #AAAAAA;
            }
        }

    }
    &__links{
        display: flex;
        justify-content: space-between;
        width: 100%;
        height: 174px;
        width: 750px;
        &-title{
            font-family: 'Gotham Pro Bold';
            font-size: 14px;
            line-height: 21px;
            color: #000;
            margin-bottom: 26px;
        }
        &-list{
            list-style-type: none;
            color: #AAAAAA;
            font-size: 13px;
            line-height: 21px;
            & li{
                margin-bottom: 17px;
                &:last-child{
                    margin-bottom: 0;
                }
            }
        }
        &-link{
            text-decoration: none;

        }
    }
    &__inst{
        width: 256px;
        height: 143px;
        text-align: right;
        &-img{
            display: flex;
            justify-content: end;
            margin-bottom: 48px;
        }
        &-text{
            font-size: 13px;
            line-height: 21px;
        }
    }
    &__text-sell{
        text-align: center;
        padding-bottom: 58px;
        color: #AAAAAA;
    }
}
</style>