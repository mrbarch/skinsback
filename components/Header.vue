<template>
  <div class="container">
    <header>
      <img src="/logo.png" class="header__logo" alt="logo">
      <div class="header__menu">
        <ul class="header__menu-list">
          <li>Продукты <img src="/arrow.svg" alt="arrow"></li>
          <li>FAQ</li>
          <li>Контакты</li>
          <li><img class="header-lang" src="/header-lang.png" alt="header-lang"></li>
          <li>
            <button class="header-button">Подключить сайт</button>
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<style lang="scss">
header {
  position: absolute;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 67vw;
  top: 0.2vw;
}

.header {
  &__bg {
    background-image: url("/header-bg.png");
    height: 112vw;
    width: 100vw;
    background-repeat: no-repeat;
    background-size: 100%;
  }
  &__logo{
    width: 10.7vw;
  }
  &__menu {
    &-list {
      font-family: "SF Pro Display", sans-serif;
      display: flex;
      width: 27vw;
      justify-content: space-between;

      li {
        font-weight: 600;
        font-size: .8vw;
        line-height: 1vw;
        display: flex;
        align-items: center;

        img {
          padding-left: 0.4vw;
        }
      }
    }
  }
  &-lang{
    width: 1vw;
    height: 1vw;
  }
  &-button {
    font-size: 0.8vw;
    line-height: 1vw;
    display: flex;
    align-items: center;
    text-align: center;
    padding: 0.5vw 1.1vw;
    background: none;
    border-radius: 5px;
    color: white;
  }
}
</style>
