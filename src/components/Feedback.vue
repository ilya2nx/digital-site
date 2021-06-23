<template>
  <div class="feedback">
    <div class="container">
      <div class="feedback__quantity">
        <img class="quantity-manuser" src="@/img/quantity-manuser.jpg" alt="man-user">
        <p class="quantity-number">10</p>
      </div>
      <h2 class="feedback__title">Отзывы наших студентов</h2>
      <div class="feedback-container">        
        <div class="feedback__card two-thirds">
          <img class="user-photo" src="@/img/user-photo1.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Настя Потураева</h5>
          <p class="card__text">Мне очень понравился курс, и в первую очередь – ваша команда. Чувствуются профессионализм и любовь к своему делу, видно, что каждый из сотрудников знает предмет до мелочей, готов развиваться и действительно хорош в своей сфере...</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>
        <div class="feedback__card third-big">
          <img class="user-photo" src="@/img/user-photo2.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Екатерина Вешниковская</h5>
          <p class="card__text">Удалось посмотреть на многие уже знакомые вещи под другим углом, и это здорово. Понравилось, что на каждую тему было отведено небольшое количество времени – мы не уставали от перегрузки какой-то одной тематикой...</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>             
        <div class="feedback__card third">
          <img class="user-photo" src="@/img/user-photo3.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Катерина Зайцева</h5>
          <p class="card__text">Очень полезное обучение, где можно услышать много практических кейсов и узнать актуальную информацию о трендах емейл-маркетинга.</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>
        <div class="feedback__card third">
          <img class="user-photo" src="@/img/user-photo4.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Ольга Константинова</h5>
          <p class="card__text">Интересный, интерактивный курс. Было много информации, инструментов для «B2C», хотелось <br /> бы добавить еще больше информации для «B2B»...</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>
        <div class="feedback__card third">
          <img class="user-photo" src="@/img/user-photo5.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Екатерина Железнова</h5>
          <p class="card__text">Я на мероприятие шла для обмена опытом. А на обучение собрались как раз ребята с разных проектов, которые действительно любят то, чем занимаются...</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>        
        <div class="feedback__card two-thirds">
          <img class="user-photo" src="@/img/user-photo6.jpg" alt="user-photo">
          <a href="#"><img class="facebook-avatarlogo" src="@/img/facebook-avatarlogo.png" alt="facebook-avatarlogo"></a>
          <h5 class="card__title">Андрей Засорин</h5>
          <p class="card__text">Ребята всегда на высоте проводят подобные мероприятия. Самое главное – практическая составляющая, всё, что услышал, я смог реализовать в работе. Особенно был интересен материал о визуальной составляющей рассылок и все самые топовые фишки в вёрстке писем...</p>
          <a href="#"><p class="card__continue">Читать далее</p></a>
        </div>
        <div class="feedback__card third-big">
          <div class="card__add">
            <img src="@/img/add-button.jpg" alt="add">
          </div>
        </div>
      </div>
      <div class="position-btn">
        <button class="btn">Загрузить еще</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

  .two-thirds {
    flex: 0 0 calc(59% - 20px);
  }
  .third {
    flex: 0 0 calc(33.33% - 20px);
  }
  .third-big {
    flex: 0 0 calc(41% - 10px);
  }

  .facebook-avatarlogo {
    margin-left: -30px;
  }

  .feedback__quantity {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 100px;

    width: 80px;
    height: 36px;
    margin-top: 165px;
    display: flex;
    .quantity-number {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 14px;
      line-height: 17px;

      color: #335381;

      width: 15px;
      height: 17px;
      margin-top: 10px;
      margin-left: 7px;
    }
    .quantity-manuser {
      width: 15px;
      height: 20px;
      margin-top: 8px;
      margin-left: 22px;
    }
  }

  .feedback__title {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 34px;
    line-height: 41px;
    text-transform: uppercase;

    color: #335381;

    text-align: center;
    margin-top: -25px;
    margin-bottom: 16px;
  }

  .position-btn {
    display: flex;
    justify-content: center;
    margin-bottom: 0px;
    .btn {
      display: none;
      border: none;
      border-radius: 2px;
      cursor: pointer;

      background: linear-gradient(180deg, #40E896 0%, #0CB27F 120.83%);
      width: 198px;
      height: 48px;
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 22px;

      text-transform: uppercase;

      color: #FFFFFF;
    }
  }

  .feedback-container {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    position: relative;
    justify-content: space-between;
    margin-bottom: 180px;
    .feedback__card {
      position: relative;
      margin-top: 32px;
      background: #FFFFFF;
      box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
      height: 350px;
      .card__title {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 22px;

        color: #404040;

        width: 103px;
        margin-left: 137px;
        margin-top: -65px;
      }
      .card__text {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 24px;

        color: #1A1A1A;

        margin-left: 32px;
        margin-right: 28px;
        margin-top: 52px;
      }
      .card__continue {
        position: absolute;
        bottom: 0;
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 22px;

        color: #0CB27F;

        width: 124px;
        margin-left: 32px;
        margin-top: 26px;
        margin-bottom: 30px;
      }
      .user-photo {
        border-radius: 100px;
        margin-top: 30px;
        margin-left: 30px;
      }
    }
    
    .card__add {
      display: flex;
      justify-content: space-around;
      padding-top: 89px;
    }
  }

  @media (max-width: 920px) {
    .feedback__quantity {
      margin-top: 137px;
    }

    .feedback-container {
      margin-bottom: 36px;
      .feedback__card {
        flex: 0 0 calc(50% - 20px);
      }
      .feedback__card:nth-child(1) {
        flex: 0 0 calc(100%);
        height: 270px;
      }
      .feedback__card:nth-child(3n+4) {
        flex: 0 0 calc(100%);
        height: 270px;
      }

      .feedback__card {
        height: 400px;
        .card__title {
          font-size: 16px;
          line-height: 20px;
        }
        .card__text {
          font-size: 14px;
          line-height: 18px;
        }
        .card__continue {
          font-size: 16px;
          line-height: 20px;
        }
        .user-photo {
          border-radius: 100px;
          margin-top: 30px;
          margin-left: 30px;
        }
      }
      
      .card__add {
        display: flex;
        justify-content: space-around;
        padding-top: 50px;
      }
    }

    .feedback__title {
      font-size: 26px;
      line-height: 32px;
    }     

    .position-btn {
      margin-bottom: 90px;
      .btn {
        display: block;
      }
    }
  }

  @media (max-width: 610px) {
    .feedback__quantity {
      margin-top: 107px;
    }

    .container {
      padding: 0 10px;
    }

    .feedback-container {
      .feedback__card {
        height: 450px;
        .card__title {
          margin-left: 110px;
          font-size: 13px;
          line-height: 18px;
        }
        .card__text {
          font-size: 13px;
          line-height: 16px;
        }
      }
    }

    .feedback__title {
      font-size: 26px;
      line-height: 32px;
      margin-top: 0;
    }   
  }

  @media (max-width: 450px) {
    .feedback__quantity {
      display: none;
    }

    .feedback__title {
      margin-top: 70px;
    }

    .feedback-container {
      .feedback__card {
        flex: 0 0 calc(100%);
        height: 350px;
      }
      .feedback__card:nth-child(1) {
        flex: 0 0 calc(100%);
        height: 350px;
      }
      .feedback__card:nth-child(3n+4) {
        flex: 0 0 calc(100%);
        height: 350px;
      }
    }

    .feedback-container {
      .feedback__card {
        height: 350px;
        .card__title {
          margin-left: 137px;
          font-size: 16px;
          line-height: 20px;
        }
        .card__text {
          font-size: 14px;
          line-height: 18px;
        }
      }
      .card__add {
        padding-top: 90px;
      }
    }
  }

  @media (max-width: 345px) {
    .feedback-container {
      .feedback__card {
        height: 380px;
      }
      .feedback__card:nth-child(1) {
        flex: 0 0 calc(100%);
        height: 380px;
      }
      .feedback__card:nth-child(3n+4) {
        flex: 0 0 calc(100%);
        height: 380px;
      }
    }
  }

  @media (max-width: 320px) {
    .feedback__quantity {
      display: none;
    }

    .feedback__title {
      margin-top: 55px;
    }

    .position-btn {
      margin-bottom: 103px;
      .btn {
        display: block;
        font-size: 14px;
        line-height: 22px;
        width: 180px;
        height: 42px;
      }
    }

    .feedback-container {
      margin-bottom: 34px;
      .feedback__card {
        height: 380px;
      }
      .feedback__card:nth-child(1) {
        flex: 0 0 calc(100%);
        height: 380px;
      }
      .feedback__card:nth-child(3n+4) {
        flex: 0 0 calc(100%);
        height: 380px;
      }
    }
  }
</style>