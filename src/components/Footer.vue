<template>
  <div class="footer">
    <div class="container">
      <div class="subscription">
        <div class="subscription__inner">
          <h2 class="subscription__title">Подпишитесь на Digital</h2>
          <p class="subscription__text">Новости, анонсы новых курсов, напоминалки — никакого спама, только самое важное.</p>
        </div>
        <div class="subscription__input">
          <input class="input" type="text">
        </div>
        <button class="btn">Хочу все знать</button>
      </div>
      <div class="checkbox-container">
        <input class="custom-checkbox" type="checkbox" name="checkbox">
        <label class="checkbox" for="checkbox"></label>
        <p class="checkbox-text">Нажимая на кнопку, вы соглашаетесь на обработку персональных данных.</p>
      </div>
      <div class="footer__links">
        <div class="footer__tagline">
          <img src="@/img/footer-logo.png" alt="footer-logo">
          <p class="tagline-text">«Современный мир требует современного образования»</p>
        </div>
        <div class="footer__courses">
          <h3 class="courses-title">Курсы</h3>
          <p class="courses-text">Цифровой маркетинг CRM-маркетинг Емейл-маркетинг Didgital Team</p>
        </div>
        <div class="footer__contacts">
          <h3 class="contacts-title">Контакты</h3>
          <p class="phone">Телефон:</p>
          <p class="phone-number">8-800-555-75-40</p>
          <p class="mail">Почта:</p>
          <p class="mail-address">experts@expertsender.ru</p>
        </div>
        <div class="footer__socials">
          <h3 class="socials-title">Соц. сети</h3>
          <img class="facebook-logo" src="@/img/footer-facebook.svg" alt="facebook-logo">
          <img class="instagram-logo" src="@/img/footer-instagram.svg" alt="instagram-logo">
        </div>
      </div>
      <div class="footer-line"></div>
      <div class="footer__copyrights">
        <p class="cookie">Политика конфиденциальности / Персональные данные / Файлы cookie</p>
        <p class="copyrights">Digital все права защищены</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .footer {
    height: 797px;
    background: linear-gradient(101.5deg, #2A4872 14.62%, rgba(12, 178, 127, 0.74) 103.36%);
  }

  .checkbox-container {
    position: relative;
    display: flex;
    margin-left: 580px;
    margin-top: -20px;
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
      border-color: #0b76ef;
      background-color: #0b76ef;
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

      width: 434px;
      height: 52px;
      margin-top: 22px;
      margin-right: 142px;
    }
    .input {
      width: 346px;
      height: 48px;
      margin-top: 186px;
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

      width: 198px;
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

  .footer__links {
    display: flex;
  }

  .footer__tagline {
    margin-top: 130px;
    .tagline-text {
      font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 28px;

    color: #FFFFFF;

    width: 255px;
    height: 84px;

    margin-top: 27px;
    }
  }

  .footer__courses {
    margin-left: 66px;
    margin-top: 134px;
    .courses-title {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 24px;
      line-height: 29px;

      color: #40E896;
    }
    .courses-text {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 36px;

      color: #FFFFFF;

      width: 207px;
      height: 144px;
      margin-top: 30px;
    }
  }

  .footer__contacts {
    margin-left: 125px;
    margin-top: 134px;
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
      width: 66px;
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
      width: 151px;
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
      width: 47px;
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
      width: 233px;
      height: 22px;
    }
  }

  .footer__socials {
    margin-top: 134px;
    margin-left: 73px;
    .socials-title {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 24px;
      line-height: 29px;

      color: #40E896;
      width: 120;
      height: 29px;
    }
    .facebook-logo {
      margin-top: 30px;
    }
    .instagram-logo {
      margin-left: 25px;
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
      width: 457px;
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
      width: 178px;
      height: 16px;
    }
  }

</style>

