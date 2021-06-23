<template>
  <div class="footer">
    <div class="container">
      <div class="subscription">
        <div class="subscription__inner">
          <h2 class="subscription__title">Подпишитесь на Digital</h2>
          <p class="subscription__text">Новости, анонсы новых курсов, напоминалки — никакого спама, только самое важное.</p>
        </div>
        <div class="subscribe">
          <input class="input" type="text" placeholder="Email">
          <button class="btn">Хочу все знать</button>
          <div class="checkbox-container">
            <input class="custom-checkbox" type="checkbox" name="checkbox">
            <label class="checkbox" for="checkbox">
              <p class="checkbox-text">Нажимая на кнопку, вы соглашаетесь на обработку персональных данных.</p>
            </label>          
          </div>
        </div>
      </div>
      <div class="footer__links">
        <div class="footer__tagline">
          <img src="@/img/footer-logo.png" alt="footer-logo">
          <p class="tagline-text">«Современный мир требует современного образования»</p>
        </div>
        <div class="footer__courses">
          <h3 class="courses-title">Курсы</h3>
          <div class="text-container">
            <a href="#"><p class="courses-text">Цифровой маркетинг</p></a>
            <a href="#"><p class="courses-text">CRM-маркетинг </p></a>
            <a href="#"><p class="courses-text">Емейл-маркетинг</p></a>
            <a href="#"><p class="courses-text">Didgital Team</p></a>
          </div>
        </div>
        <div class="footer__contacts">
          <h3 class="contacts-title">Контакты</h3>
          <p class="phone">Телефон:</p>
          <a href="8-800-555-75-40"><p class="phone-number">8-800-555-75-40</p></a>
          <p class="mail">Почта:</p>
          <a href="experts@expertsender.ru"><p class="mail-address">experts@expertsender.ru</p></a>
        </div>
        <div class="footer__socials">
          <h3 class="socials-title">Соц. сети</h3>
          <a href="#">
            <img class="facebook-logo" src="@/img/footer-facebook.svg" alt="facebook-logo">
          </a>
          <a href="#">
            <img class="instagram-logo" src="@/img/footer-instagram.svg" alt="instagram-logo">
          </a>
        </div>
      </div>
      <div class="footer-line"></div>
      <div class="footer__copyrights">
        <a href="#"><p class="cookie">Политика конфиденциальности / Персональные данные / Файлы cookie</p></a>
        <a href="#"><p class="copyrights"><span>Digital</span> Все права защищены</p></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  a {
    text-decoration: none;
  }

  .footer {
    height: 797px;
    position: relative;
    background-image: url('../img/footer-background.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top center;
  }

  .checkbox-container {
    position: relative;
    display: flex;
    margin-top: 15px;
    .custom-checkbox {
      position: absolute;
      opacity: 0;
    }
    .custom-checkbox+label {
      display: inline-flex;
      align-items: center;
      user-select: none;
    }
    .custom-checkbox+label::before {
      content: '';
      display: inline-block;
      width: 1em;
      height: 1em;
      flex-shrink: 0;
      flex-grow: 0;
      border: 1px solid #ffffff;
      border-radius: 50%;
      margin-right: 0.5em;
      background-repeat: no-repeat;
      background-position: center center;
      background-size: 50% 50%;
    }
    .custom-checkbox:checked+label::before {
      border-color: #40E896;
      background-color: #40E896;
      background: inherit;
      background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3e%3c/svg%3e");
    }
    .checkbox-text {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 12px;
      line-height: 22px;

      color: #FFFFFF;
    }
  }

  .subscription {
    display: flex;
    justify-content: space-between;
    width: 100%;
    .subscription__inner {
      width: 40%;
      .subscription__title {
        font-family: 'Lato', sans-serif;
        font-style: normal;
        font-weight: bold;
        font-size: 34px;
        line-height: 41px;

        color: #40E896;

        width: 229px;
        height: 82px;

        margin-top: 115px;
      }
      .subscription__text {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 26px;

        color: #FFFFFF;

        height: 52px;
        margin-top: 22px;
      }
    }
    .subscribe {
      display: flex;
      flex-wrap: wrap;
      width: 48%;
      .input {
        width: 64%;
        height: 48px;
        margin-top: 186px;
        padding: 15px;
        border: none;
        background: #FFFFFF;
        border: 1px solid #FFFFFF;
        box-sizing: border-box;
        border-radius: 2px 0 0 2px;
      }
      .btn {
        background: linear-gradient(180deg, #40E896 0%, #0CB27F 120.83%);
        border: none;
        border-radius: 0 2px 2px 0;
        cursor: pointer;

        width: 36%;
        height: 48px;
        margin-top: 186px;

        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 22px;

        text-transform: uppercase;

        color: #FFFFFF;
      }
    }
  }

  .footer__links {
    display: flex;
    justify-content: space-between;
    width: 100%;
    .footer__tagline {
      margin-top: 130px;
      width: 20%;
      .tagline-text {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 28px;

      color: #FFFFFF;

      height: 84px;

      margin-top: 27px;
      }
    }
    .footer__courses {
      margin-top: 134px;
      width: 19%;
      .courses-title {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 29px;
        margin-bottom: 30px;

        color: #40E896;
      }
      .courses-text {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 36px;

        color: #FFFFFF;

      }
    }
    .footer__contacts {
      margin-top: 134px;
      width: 17%;
      .contacts-title {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 29px;

        color: #40E896;
      }
      .phone {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 22px;

        color: #FFFFFF;

        margin-top: 30px;
        height: 22px;
      }
      .phone-number {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 22px;

        color: #FFFFFF;

        margin-top: 4px;
        height: 22px;
      }
      .mail {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 22px;

        color: #FFFFFF;

        margin-top: 32px;
        height: 22px;
      }
      .mail-address {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 22px;

        color: #FFFFFF;

        margin-top: 4px;
        height: 22px;
      }
    }
    .footer__socials {
      margin-top: 134px;
      width: 14%;
      .socials-title {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 29px;

        color: #40E896;
        height: 29px;
      }
      .facebook-logo {
        margin-top: 30px;
      }
      .instagram-logo {
        margin-left: 25px;
      }
    }
  }


  .footer-line {
    opacity: 0.4;
    border-radius: 4px;
    border-bottom: 1px solid white;
    margin-top: 98px;
  }

  .footer__copyrights {
    display: flex;
    justify-content: space-between;
    .cookie {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 12px;
      line-height: 16px;

      color: #FFFFFF;

      margin-top: 37px;
      height: 18px;
    }
    .copyrights {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 12px;
      line-height: 16px;

      text-align: right;

      color: #FFFFFF;

      margin-top: 38px;
      height: 16px;
    }
  }

  @media (max-width: 900px) {
    .footer {
      background-image: url('../img/footer-background-ipad.jpg');
    }

    .checkbox-container {
      margin-top: 0px;
      .checkbox-text {
        font-size: 12px;
        line-height: 14px;
      }
    }

    .subscription {
      width: 100%;
      .subscription__inner {
        width: 40%;
        .subscription__title {
          font-size: 26px;
          line-height: 31px;

          width: 209px;
          margin-top: 200px;
        }
        .subscription__text {
          font-size: 14px;
          line-height: 18px;

          height: 52px;
          margin-top: 0px;
        }
      }
      .subscribe {
        width: 55%;
        .input {
          width: 58%;
          height: 38px;
          margin-top: 230px;
        }
        .btn {
          width: 42%;
          height: 38px;
          margin-top: 230px;

          font-size: 14px;
          line-height: 22px;

        }
      }
    }

    .footer__links {
      width: 100%;
      .footer__tagline {
        display: none;
      }
      .footer__courses {
        margin-top: 129px;
        width: 30%;
        .courses-title {
          font-size: 18px;
          line-height: 22px;
          margin-bottom: 21px;
        }
        .courses-text {
          font-size: 14px;
          line-height: 28px;
        }
      }
      .footer__contacts {
        margin-top: 129px;
        width: 30%;
        .contacts-title {
          font-size: 18px;
          line-height: 22px;
        }
        .phone {
          font-size: 12px;
          line-height: 22px;;

          margin-top: 21px;
        }
        .phone-number {
          font-size: 14px;
          line-height: 17px;

          margin-top: 4px;
          height: 17px;
        }
        .mail {
          font-size: 12px;
          line-height: 22px;

          margin-top: 21px;
          height: 22px;
        }
        .mail-address {
          font-size: 14px;
          line-height: 17px;

          margin-top: 4px;
          height: 17px;
        }
      }
      .footer__socials {
        margin-top: 129px;
        width: 15%;
        .socials-title {
          font-size: 18px;
          line-height: 22px;

          height: 29px;
        }
        .facebook-logo {
          margin-top: 21px;
          width: 26px;
          height: 26px;
        }
        .instagram-logo {
          margin-left: 20px;
          width: 26px;
          height: 26px;
        }
      }
    }


    .footer-line {
      margin-top: 45px;
    }

    .footer__copyrights {
      .cookie {
        font-size: 12px;
        line-height: 18px;

        margin-top: 32px;
        height: 36px;
      }
      .copyrights {
        font-size: 12px;
        line-height: 18px;

        margin-top: 32px;
        height: 36px;
      }
      .copyrights::after {
        content: ' © 2018-2019 ООО «ЭНКОД»';
      }
      span {
        display: none;
      }
    }
  }

  @media (max-width: 601px) {
    .subscription {
      .subscribe {
        .btn {
          font-size: 12px;
          line-height: 18px;
        }
      }
    }

    .footer__links {
      .footer__socials {
        width: 19%;
        .socials-title {
          font-size: 16px;
          line-height: 20px;
        }
      }
    }
  }

  @media (max-width: 425px) {
    .footer {
      height: 900px;
      background-image: url('../img/footer-background-phone.jpg');
      padding: 0 20px;
    }

    .checkbox-container {
      margin-top: 20px;
      width: 90%;
      .checkbox-text {
        font-size: 12px;
        line-height: 14px;
      }
    }

    .subscription {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      width: 100%;
      .subscription__inner {
        width: 100%;
        .subscription__title {
          font-size: 22px;
          line-height: 26px;

          width: 100px;
          height: 52px;

          margin-top: 101px;
        }
        .subscription__text {
          font-size: 14px;
          line-height: 18px;

          width: 250px;
          height: 54px;
          margin-top: 22px;
        }
      }
      .subscribe {
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        .input {
          width: 80%;
          height: 48px;
          margin-top: 30px;
          margin-left: 20px;
        }
        .btn {
          width: 60%;
          height: 38px;
          margin-top: 10px;
          margin-left: 20px;

          font-size: 14px;
          line-height: 22px
        }
      }
    }

    .footer__links {
      flex-wrap: wrap;
      width: 100%;
      .footer__tagline {
        display: none;
      }
      .footer__courses {
        margin-top: 120px;
        width: 100%;
      
        .courses-title {
          font-size: 14px;
          line-height: 17px;
          margin-bottom: 16px;
        }
        .text-container {
          display: flex;
          flex-wrap: wrap;
          justify-content: space-between;
          .courses-text {          
            font-size: 12px;
            line-height: 24px;
            padding-right: 30px;
          }
        }
      }
      .footer__contacts {
        margin-top: 30px;
        width: 60%;
        .contacts-title {
          font-size: 14px;
          line-height: 17px;
        }
        .phone {
          display: none;
        }
        .phone-number {
          font-size: 12px;
          line-height: 15px;

          margin-top: 19px;
          height: 15px;
        }
        .mail {
          display: none;
        }
        .mail-address {
          font-size: 12px;
          line-height: 15px;

          margin-top: 10px;
          height: 15px;
        }
      }
      .footer__socials {
        margin-top: 30px;
        width: 30%;
        .socials-title {
          font-size: 14px;
          line-height: 17px;

          height: 17px;
        }
        .facebook-logo {
          margin-top: 19px;
        }
        .instagram-logo {
          margin-left: 12px;
        }
      }
    }


    .footer-line {
      margin-top: 17px;
    }

    .footer__copyrights {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .cookie {
        font-size: 12px;
        line-height: 18px;

        margin-top: 25px;
        height: unset;
      }
      .copyrights {
        font-size: 12px;
        line-height: 16px;
        
        width: 50%;
        margin-top: 20px;
        height: 16px;
        text-align: left;
      }
    }
  }

  @media (max-width: 320px) {
    .footer {
      height: 900px;
      background-image: url('../img/footer-background-phone.jpg');
      padding: unset;
    }

    .checkbox-container {
      margin-top: 20px;
      width: 100%;
      .checkbox-text {
        font-size: 12px;
        line-height: 14px;
      }
    }

    .subscription {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      width: 100%;
      .subscription__inner {
        width: 100%;
        .subscription__title {
          font-size: 22px;
          line-height: 26px;

          width: 100px;
          height: 52px;

          margin-top: 101px;
        }
        .subscription__text {
          font-size: 14px;
          line-height: 18px;

          width: 250px;
          height: 54px;
          margin-top: 22px;
        }
      }
      .subscribe {
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        .input {
          width: 100%;
          height: 48px;
          margin-top: 30px;
        }
        .btn {
          width: 60%;
          height: 38px;
          margin-top: 10px;
          margin-left: 120px;

          font-size: 14px;
          line-height: 22px
        }
      }
    }

    .footer__links {
      flex-wrap: wrap;
      width: 100%;
      .footer__tagline {
        display: none;
      }
      .footer__courses {
        margin-top: 120px;
        width: 100%;
      
        .courses-title {
          font-size: 14px;
          line-height: 17px;
          margin-bottom: 16px;
        }
        .text-container {
          display: flex;
          flex-wrap: wrap;
          justify-content: space-between;
          .courses-text {          
            font-size: 12px;
            line-height: 24px;
            padding-right: 30px;
          }
        }
      }
      .footer__contacts {
        margin-top: 30px;
        width: 60%;
        .contacts-title {
          font-size: 14px;
          line-height: 17px;
        }
        .phone {
          display: none;
        }
        .phone-number {
          font-size: 12px;
          line-height: 15px;

          margin-top: 19px;
          height: 15px;
        }
        .mail {
          display: none;
        }
        .mail-address {
          font-size: 12px;
          line-height: 15px;

          margin-top: 10px;
          height: 15px;
        }
      }
      .footer__socials {
        margin-top: 30px;
        width: 30%;
        .socials-title {
          font-size: 14px;
          line-height: 17px;

          height: 17px;
        }
        .facebook-logo {
          margin-top: 19px;
        }
        .instagram-logo {
          margin-left: 12px;
        }
      }
    }


    .footer-line {
      margin-top: 17px;
    }

    .footer__copyrights {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .cookie {
        font-size: 12px;
        line-height: 18px;

        margin-top: 25px;
        height: unset;
      }
      .copyrights {
        font-size: 12px;
        line-height: 16px;
        
        width: 50%;
        margin-top: 20px;
        height: 16px;
        text-align: left;
      }
    }
  }

</style>

