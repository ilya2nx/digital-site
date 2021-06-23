<template>
  <div class="header">
    <div class="container__header">
      <div class="header__top">
        <img class="logo__img" src="@/img/logo.svg" alt="logo">
        <div class="header__buttons">
          <a href="#" class="header__button">курсы</a>
          <a href="#" class="header__button">о компании</a>
          <a href="#" class="header__button">отзывы</a>
          <a href="#" class="header__button">контакты</a>
        </div>
        <img class="burger" src="@/img/burger.png" alt="burger">
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
    height: 450px;
    width: 100%;
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
    .burger {
      display: none;
    }

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

      width: 56%;

      color: #FFFFFF;
    }
  }

  @media (max-width: 950px) {
    .header__top {
      .header__buttons {
        font-family: 'Lato', sans-serif;
        font-weight: 400;
        font-size: 18px;
        line-height: 21.6px;
        .header__button {
          height: 40px;
          width: 130px;
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
  }

  @media (max-width: 900px) {
    .header {
      position: relative;
      background-image: url('../img/header-background-ipad.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      background-position: top center;
      height: 338px;
      width: 100%;
    }

    .container__header {
      max-width: 680px;
      padding: 0 0;
    }
    .logo__img {
      width: 180px;
      height: 31px;
      margin-top: 20px;
    }
    .header__top {
      .header__buttons {
        font-size: 12px;
        line-height: 14px;
        .header__button {
          width: 90px;
          height: 26px;
          border: 1px solid #40E896;
          box-sizing: border-box;
          border-radius: 2px;
          padding-top: 5px;
          opacity: 0.8;
        }
        .header__button:nth-child(3) {
          display: none;
        }
      }
    }
    .header__content {
      padding-top: 20px;
      padding-left: 0;
      .header__title {
        font-size: 26px;
        line-height: 32px;
        padding-bottom: 16px;
      }
      .header__text {
        font-size: 14px;
        line-height: 18px;
        width: 58%;
        height: 54px;
      }
    }
  }

  @media (max-width: 490px) {
    .header__top {
      .header__buttons {
        font-size: 12px;
        line-height: 14px;
        .header__button {
          width: 70px;
          height: 26px;
          border: 1px solid #40E896;
          box-sizing: border-box;
          border-radius: 2px;
          padding-top: 5px;
          opacity: 0.8;
        }
        .header__button:nth-child(3) {
          display: none;
        }
      }
    }
  }

  @media (max-width: 430px) {
    .header__top {
      padding-top: 10px;
      .header__buttons {
        display: none;
      }
      .burger {
        display: block;
        padding-right: 13px;
      }
    }
  }

  @media (max-width: 320px) {
    .header {
      position: relative;
      background-image: url('../img/header-background-phone.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      background-position: top center;
      height: 326px;
      width: 100%;
    }

    .container__header {
      max-width: 320px;
      padding: 0 16px;
    }
    .logo__img {
      width: 160px;
      height: 28px;
      margin-top: 20px;
    }
    .header__top {
      padding-top: 10px;
      .header__buttons {
        display: none;
      }
      .burger {
        display: block;
        padding-right: 13px;
      }
    }

    .header__content {
      padding-top: 20px;
      .header__title {
        font-size: 22px;
        line-height: 27px;
        padding-bottom: 14px;
      }
      .header__text {
        font-size: 14px;
        line-height: 18px;
        width: 100%;
        height: 90px;
      }
    }
  }
</style>