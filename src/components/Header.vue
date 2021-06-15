<template>
  <div class="header">
    <div class="gradient"></div>
    <div class="green-dots"></div>
    <div class="band"></div>
    <div class="container__header">
      <div class="header__top">
        <img class="logo__img" src="@/img/logo.svg" alt="logo">
        <div class="header__buttons">
          <a href="#" class="header__button">курсы</a>
          <a href="#" class="header__button">о компании</a>
          <a href="#" class="header__button">отзывы</a>
          <a href="#" class="header__button">контакты</a>
        </div>
      </div>
      <div class="header__content">
        <h2 class="header__title">Отзывы</h2>
        <p class="header__text">Мы вкладываем в обучение все свои силы, знания и энтузиазм.
          Обратная связь от наших учеников — показатель того, что мы все делаем правильно.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .header {
    position: relative;
    background-image: url('../img/header-background.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top center;
    min-height: 450px;
    z-index: -4;
    .gradient {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/gradient.png') center center / cover no-repeat;
      z-index: -3;
    }
    .green-dots {
      background: url('../img/green-dots.png') center center / cover no-repeat;
      z-index: -1;
      position: absolute;
      height: 100%;
      width: 100%;
      max-width: 1300px;
      left: -20px;
      right: 0;
      margin: auto;
    }
    .band {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/band.png') center center / cover no-repeat;
      z-index: -2;
    }
  }

  a {
    text-decoration: none;
    color: white;
    display: inline-block;
  }

  .container__header {
    max-width: 1300px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 10px;
  }

  .header__top {
    padding: 24px 0 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  
    .header__buttons {
      font-family: 'Lato', sans-serif;
      font-weight: 400;
      font-size: 18px;
      line-height: 21.6px;
      .header__button {
        height: 40px;
        width: 155px;
        border: 1px solid #FFFFFF;
        box-sizing: border-box;
        border-radius: 2px;
        text-align: center;
        padding-top: 9px;
      }
      .header__button:not(:last-child) {
        margin-right: 20px;
      }
    }
  }
  
  .header__content {
    max-width: 1140px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 10px;
    padding-top: 91.7px;
    .header__title {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 34px;
      line-height: 41px;

      padding-bottom: 24px;

      color: #40E896;
    }
    .header__text {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 26px;

      max-width: 650px;

      color: #FFFFFF;
    }
  }
</style>