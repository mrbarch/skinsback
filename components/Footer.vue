<template>
  <footer>
    <div class="footer">
      <div class="footer__blocks">
        <div class="footer__block footer__block-col1">
          <img src="/logo.png" class="footer__block-col1-logo" alt="logo">
          <ul class="footer__block-col1-menu">
            <li class="footer__block-col1-menu-list">FAQ</li>
            <li class="footer__block-col1-menu-list">Контакты</li>
            <li class="footer__block-col1-menu-list">Пользовательское соглашение</li>
          </ul>
        </div>
        <div class="footer__block footer__block-col2">
          <ul class="footer__block-col2-menu">
            <li class="footer__block-col2-menu-list">Получение платежей</li>
            <li class="footer__block-col2-menu-list">Вывод скинов</li>
            <li class="footer__block-col2-menu-list">Продажа скинов</li>
          </ul>
        </div>
        <div class="footer__block footer__block-col3">
          <div class="footer__block-col3-title">Связаться с нами</div>
          <img src="/footer-logo.png" alt="" class="footer__block-col3-img">
          <button class="footer__block-col3-button">Скачать презентацию</button>
        </div>
      </div>
      <div class="footer__copyrights">
        Copyright © 2018 - 2021. All Rights Reserved.
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
.footer {
  padding-top: 2.2vw;
  width: 52vw;
  margin: 0 auto;
  &__blocks {
    display: flex;
    justify-content: space-between;
  }
  &__block {
    &-col1 {
      &-logo {
        width: 10.4vw;
      }
      &-menu {
        display: flex;
        flex-direction: column;
        padding: 0;
        font-family: SFProDisplay, sans-serif;
        font-style: normal;
        font-weight: 200;
        font-size: 0.7vw;
        line-height: 1.2vw;
        letter-spacing: -.03vw;
        color: #FEFFFF;
      }
    }
  }
  .footer__block-col2 {
    width: 21vw;
    height: 1vw;
    &-menu {
      display: flex;
      justify-content: space-between;
      flex-direction: row;
      padding: 0;
      font-family: SFProDisplay, sans-serif;
      font-style: normal;
      font-weight: 300;
      font-size: 0.7vw;
      line-height: 1.2vw;
      letter-spacing: -.03vw;
      color: #FEFFFF;
      width: 18.4vw;
      margin-top: 0;
    }

  }
  .footer__block-col3 {
    width: 8vw;
    &-title {
      font-family: SFProDisplay, sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 0.7vw;
      line-height: 1.2vw;
      display: flex;
      align-items: center;
      color: #A2AAAF;
      letter-spacing: -0.05vw;
    }
    &-img {
      padding: 0.3vw;
      width: 1vw;
    }
    &-button {
      margin-top: 0.5vw;
      margin-left: 0.3vw;
      height: 1.6vw;
      border: 1px solid #7F9CFC;
      box-sizing: border-box;
      border-radius: 5px;
      color: #7A98F6;
      font-size: 0.6vw;
      line-height: 0.7vw;
      background-color: transparent;
      padding: 0;
      width: 7.7vw;
    }
  }
  &__copyrights {
    text-align: center;
    padding-top: 1.3vw;
    font-family: SFProDisplay, sans-serif;
    font-style: normal;
    font-weight: 100;
    font-size: 0.54vw;
    line-height: 1.2vw;
    color: #FEFFFF;
  }
}
footer {
  background: #1D1E34;
  width: 100%;
  height: 11.8vw;
  position: relative;
  top: -8.5vw;

}

</style>
