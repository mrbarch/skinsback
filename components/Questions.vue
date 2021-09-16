<template>

  <div class="questions">
    <div class="container__questions">
      <div class="questions__title">Остались вопросы?</div>
      <div class="questions__subtitle title__h4">Напишите нам и мы обязательно вам ответим</div>
      <div class="questions__blocks">
        <div class="questions__block">
          <div class="questions__block-title">По вопросам подключания:</div>
          <div class="questions__block-table">
            <img src="/telegram.png" alt="telegram" class="questions__block-table-img-telegram">
            <div class="questions__block-table-text">@skinsback</div>
          </div>
          <div class="questions__block-table">
            <img src="/mail.png" alt="mail" class="questions__block-table-img-mail">
            <div class="questions__block-table-text">admin@skinsback.com</div>
          </div>
        </div>
        <div class="questions__block">
          <div class="questions__block-title">По другим вопросам:</div>
          <div class="questions__block-table">
            <img src="/telegram.png" alt="telegram" class="questions__block-table-img-telegram">
            <div class="questions__block-table-text">@skinsback_support</div>
          </div>
          <div class="questions__block-table">
            <img src="/mail.png" alt="mail" class="questions__block-table-img-mail">
            <div class="questions__block-table-text">support@skinsback.com</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.container__questions {
  width: 31vw;
  margin: 0 auto;
}
.questions {
  background-image: url(/questions-bg.png);
  background-repeat: no-repeat;
  width: 100%;
  height: 26.9vw;
  position: relative;
  top: -7vw;
  background-size: contain;;

  &__blocks {
    padding-top: 2.7vw;
    display: flex;
    justify-content: space-between;
  }

  &__block {
    display: flex;
    flex-direction: column;
    &-title {
      font-family: SFProDisplay, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 0.81vw;
      line-height: 1.1vw;
      display: flex;
      align-items: center;

      color: #FEFFFF;
    }
    &-table {
      border: 1px solid #7F9CFC;
      box-sizing: border-box;
      margin-top: 1.1vw;
      height: 4vw;
      width: 13.1vw;
      display: flex;
      &-img {
        &-telegram {
          height: 2vw;
          width: 2.5vw;
          padding-top: 0.5vw;
          padding-left: 0.5vw;
        }
        &-mail {
          height: 1.5vw;
          width: 2.3vw;
          padding-top: 0.6vw;
          padding-left: 0.6vw;
        }
      }
      &-text {
        font-family: SFProDisplay, sans-serif;
        font-style: normal;
        font-weight: bolder;
        font-size: 0.7vw;
        line-height: 2vw;
        color: #FEFFFF;
        position: relative;
        right: 1vw;
        letter-spacing: 0.05vw;
        top: 1vw;
      }
    }
  }

  &__title {
    font-weight: 600;
    font-size: 1.5vw;
    line-height: 1.7vw;
    text-align: center;
    color: #FEFFFF;
    position: relative;
    z-index: 1;
    padding-top: 5.4vw;

    &:before {
      font-family: SFProDisplay, sans-serif;
      content: "Вопросы?";
      font-weight: 600;
      font-size: 4.2vw;
      line-height: 5vw;
      justify-content: center;
      align-items: center;
      top: 3vw;
      left: 5.5vw;
      position: absolute;
      z-index: -1;
      letter-spacing: -0.16vw;
      color: #FEFFFF;
      opacity: 0.05;
    }
  }

  &__subtitle {
    text-align: center;
    padding-top: 0.6vw;
    letter-spacing: -0.06vw;
  }
}
</style>
