<template>
  <div class="container">
    <header>
      <img src="/logo.png" class="header__logo" alt="logo">
      <div class="header__menu">
        <ul class="header__menu-list title__h4">
          <li>Продукты <img src="/arrow-header.png" alt="arrow"></li>
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
    height: 35vw;
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
        display: flex;
        align-items: center;
        img {
          padding-left: 0.4vw;
        }
      }
    }
  }
  &-lang{
    width: 1.3vw;
    height: 1.3vw;
  }
  &-button {
    font-weight: 600;
    display: flex;
    align-items: center;
    background: none;
    border-radius: 8px;
    color: white;
    width: 8.8vw;
    height: 2vw;
    justify-content: center;
    letter-spacing: 0.05vw;
  }
}
</style>
