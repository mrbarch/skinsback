<template>
  <div class="header__bg">
    <div class="container">
      <section class="connect">
        <div class="connect__title">Получение платежей игровыми предметами CS:GO и Dota 2 для онлайн-бизнеса</div>
        <div class="connect__subtitle">
          Сервис с быстрым подключением
          и современным API
        </div>
        <button class="connect__button">Подключить сайт</button>
        <div class="connect__border-left"></div>
        <div class="connect__border-right"></div>
      </section>
      <div class="price">
        <div class="price__bg">
          <div class="price__bg-weapon">
            <div class="price__bg-weapon-top"></div>
            <div class="price__bg-weapon-left"></div>
            <div class="price__bg-weapon-right"></div>
            <div class="price__bg-weapon-center"></div>
          </div>
        </div>
        <div class="price__info">
          <div class="price__info-title">Что такое скины</div>
          <div class="price__info-subtitle">Новая цифровая валюта</div>
        </div>
        <div class="price__info-text">Скины - важная часть культуры Counter-Strike: Global Offensive и Dota 2. Ими
          пользуются миллионы игроков и воспринимают их как валюту.
        </div>
        <div class="price__info-blocks">
          <div class="price__info-block">
            <img src="/price-info-1.png" class="price__info-block-skin" alt="price-info-skin">
            <img src="/price-info-2.png" class="price__info-block-skin" alt="price-info-skin">
            <img src="/price-info-3.png" class="price__info-block-skin" alt="price-info-skin">
            <img src="/price-info-4.png" class="price__info-block-skin" alt="price-info-skin">
          </div>
          <img src="/price-info-arrow.png" class="price__info-blocks-arrow" alt="info-arrow">
        </div>
      </div>
    </div>
    <div class="payment container">
      <div class="payment__border-left"></div>
      <div class="payment__border-right"></div>
      <div class="payment__title">Новый способ оплаты на вашем сайте</div>
      <div class="payment__subtitle">Сделайте свой бизнес в Сети более эффективным</div>
      <ul class="payment__info">
        <li class="payment__info-list">
          <img class="payment__info-img" src="/payment-info-1.png" alt="payment-info">
          <div class="payment__info-title">
            Удобная и понятная форма оплаты
          </div>
          <div class="payment__info-subtitle">
            Минимальное количество
            ошибочных или отклоненных
            платежей
          </div>
        </li>
        <li class="payment__info-list">
          <img class="payment__info-img" src="/payment-info-2.png" alt="payment-info">
          <div class="payment__info-title">
            Отсутствие  комиссии
          </div>
          <div class="payment__info-subtitle">
            Все средства в полном объеме поступают на ваш депозит
          </div></li>
        <li class="payment__info-list">
          <img class="payment__info-img" src="/payment-info-3.png" alt="payment-info">
          <div class="payment__info-title">
            Никаких скрытых платежей
          </div>
          <div class="payment__info-subtitle">
            Бесплатное подключение,
            без абонентской платы
          </div></li>
        <li class="payment__info-list">
          <img class="payment__info-img" src="/payment-info-4.png" alt="payment-info">
          <div class="payment__info-title">
            Полный контроль
            всех платежей
          </div>
          <div class="payment__info-subtitle">
            Все операции в режиме реального времени отображаются в личном кабинете
          </div></li>
      </ul>
    </div>
  </div>
</template>


<style lang="scss">
.connect {
  padding-left: 7.4vw;

  &__title {
    padding-top: 10.2vw;
    font-style: normal;
    width: 27vw;
    font-weight: 600;
    font-size: 2vw;
    line-height: 2.5vw;
    display: flex;
    align-items: center;
  }

  &__subtitle {
    margin-top: 0.8vw;
    width: 17vw;
    font-weight: 600;
    font-size: 0.9vw;
    line-height: 1vw;
    display: flex;
    align-items: center;
  }

  &__button {
    background: linear-gradient(93.82deg, #7D8FF9 5.29%, #325BC2 107.98%);
    border-radius: 5px;
    padding: 1.1vw 2.48vw;
    margin-top: 2.3vw;
    font-weight: 600;
    font-size: 0.9vw;
    line-height: 1vw;
    display: flex;
    align-items: center;
    text-align: center;
  }

  &__border-left {
    position: relative;
    right: 24.2vw;
    top: 1vw;
    width: 24.3vw;
    border-bottom: 0.3vw solid white;
    transform: rotate(-170deg);
  }

  &__border-right {
    position: relative;
    left: 10.2vw;
    top: 4.1vw;
    width: 66vw;
    border-bottom: 0.3vw solid #1D1E34;
    transform: rotate(175.5deg);
  }
}

.price {
  height: 22.4vw;
  padding-left: 6.4vw;

  &__bg {
    background-image: url(/value-bg.png);
    background-repeat: no-repeat;
    background-size: 31.2vw;
    width: 40.2vw;
    height: 35vw;
    position: absolute;
    left: 0;
    top: 29.5vw;

    &-weapon {
      &-top {
        background-image: url(/header-weapon-1.png);
        background-repeat: no-repeat;
        background-size: 9vw;
        width: 9vw;
        height: 9vw;
        position: relative;
        left: 31.4vw;
        top: 12vw;
      }

      &-left {
        background-image: url(/header-weapon-2.png);
        background-repeat: no-repeat;
        background-size: 8vw;
        width: 7.5vw;
        height: 7.5vw;
        position: relative;
        left: 22.7vw;
        top: 8vw;
      }

      &-right {
        background-image: url(/header-weapon-3.png);
        background-repeat: no-repeat;
        background-size: 9vw;
        width: 9.5vw;
        height: 8.4vw;
        position: relative;
        left: 31.7vw;
        top: 6vw;
      }

      &-center {
        background-image: url(/rhombus.png);
        background-repeat: no-repeat;
        background-size: 3.4vw;
        width: 4vw;
        height: 5vw;
        position: relative;
        left: 30.4vw;
        bottom: 5.8vw;
      }
    }
  }

  &__info {
    padding-right: 6vw;

    &-title {
      font-weight: 600;
      font-size: 4vw;
      line-height: 5vw;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #F1F6F9;
      margin-top: 7.5vw;
    }

    &-subtitle {
      position: relative;
      font-weight: 600;
      font-size: 1.5vw;
      line-height: 1.8vw;
      display: flex;
      align-items: center;
      text-align: center;
      color: #1D1E34;
      justify-content: center;
      top: -2.5vw;
    }

    &-text {
      padding-top: 2.2vw;
      padding-left: 18.6vw;
      font-weight: normal;
      font-size: 0.8vw;
      line-height: 1vw;
      display: flex;
      align-items: center;
      color: #1D1E34;
      justify-content: center;
      padding-right: 6vw;
    }

    &-blocks {
      display: flex;
      justify-content: space-between;
      width: 42.3vw;
      padding-left: 18.6vw;
      padding-top: 2.3vw;

      &-arrow {
        width: 3vw;
        height: 3vw;
        position: relative;
        bottom: 1vw;
      }
    }

    &-block {
      display: flex;
      justify-content: space-between;
      width: 34.2vw;
      &-skin {
        width: 7.5vw;
        height: 9.2vw;
      }
    }
  }
}
.payment {
  font-family: "SF Pro Display", sans-serif;
  background-image: url("/payment-bg.png");
  height: 112vw;
  width: 100%;
  background-repeat: no-repeat;
  background-size: 100%;
  &__border-left {
    border-top: 4.3px solid #FEFFFF;
    transform: rotate(-175.8deg);
    position: relative;
    left: 0;
    top: 3.7vw;
    width: 65.3vw;
  }
  &__border-right {
    border-top: 4.3px solid #F1F6F9;
    transform: rotate(169.8deg);
    position: absolute;
    left: 75.6vw;
    top: 59.8vw;
    width: 23.3vw;
  }
  &__title {
    font-weight: 600;
    font-size: 1.5vw;
    line-height: 1.7vw;
    text-align: center;
    color: #1D1E34;
    padding-top: 10vw
  }
  &__subtitle {
    font-size: 0.83vw;
    line-height: 0.7vw;
    text-align: center;
    color: #1D1E34;
    margin-top: 1vw;
  }
  &__info {
    display: flex;
    justify-content: center;
    margin-top: 5.5vw;
    padding-left: 16vw;
    padding-right: 4vw;

    position: relative;
    &::before {
      content: '';
      background: linear-gradient(98.46deg, #293F90 0.47%, #1D1E34 84.33%);
      position: absolute;
      height: 0.3vw;
      width: 52vw;
      top: 4vw;
      z-index: 0;
      margin-right: 6.9vw;
    }

    &-img {
      z-index: 1;
      position: relative;
      display: flex;
      justify-items: center;
    }
    &-list {
      width: 15vw;
    }
    &-title {
      width: 3vw;
    }
    &-subtitle {
      width: 3vw;
    }
  }
}
</style>
