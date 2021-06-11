<template>
  <div class="feedback">
    <div class="container">
      <h2 class="feedback__title">Отзывы наших студентов</h2>
      <div class="feedback__content-firstline">
        <div class="feedback__firstline-card1">
          <img class="user-photo1" src="@/img/user-photo1.jpg" alt="user-photo">
          <h5 class="feedback__firstline-title1">Настя Потураева</h5>
          <p class="feedback__firstline-text1">Мне очень понравился курс, и в первую очередь – ваша команда. Чувствуются профессионализм и любовь к своему делу, видно, что каждый из сотрудников знает предмет до мелочей, готов развиваться и действительно хорош в своей сфере...</p>
          <p class="feedback__firstline-continue1">Читать далее</p>
        </div>
        <div class="feedback__firstline-card2">
          <img class="user-photo2" src="@/img/user-photo2.jpg" alt="user-photo">
          <h5 class="feedback__firstline-title2">Екатерина Вешниковская</h5>
          <p class="feedback__firstline-text2">Удалось посмотреть на многие уже знакомые вещи под другим углом, и это здорово. Понравилось, что на каждую тему было отведено небольшое количество времени – мы не уставали от перегрузки какой-то одной тематикой...</p>
          <p class="feedback__firstline-continue2">Читать далее</p>
        </div>
      </div>
      <div class="feedback__content-secondline">
        <div class="feedback__secondline-card3">
          <img class="user-photo3" src="@/img/user-photo3.jpg" alt="user-photo">
          <h5 class="feedback__secondline-title3">Катерина Зайцева</h5>
          <p class="feedback__secondline-text3">Очень полезное обучение, где можно услышать много практических кейсов и узнать актуальную информацию о трендах емейл-маркетинга.</p>
          <p class="feedback__secondline-continue3">Читать далее</p>
        </div>
        <div class="feedback__secondline-card4">
          <img class="user-photo4" src="@/img/user-photo4.jpg" alt="user-photo">
          <h5 class="feedback__secondline-title4">Ольга Константинова</h5>
          <p class="feedback__secondline-text4">Интересный, интерактивный курс. Было много информации, инструментов для «B2C», хотелось <br /> бы добавить еще больше информации для «B2B»...</p>
          <p class="feedback__secondline-continue4">Читать далее</p>
        </div>
        <div class="feedback__secondline-card5">
          <img class="user-photo5" src="@/img/user-photo5.jpg" alt="user-photo">
          <h5 class="feedback__secondline-title5">Екатерина Железнова</h5>
          <p class="feedback__secondline-text5">Я на мероприятие шла для обмена опытом. А на обучение собрались как раз ребята с разных проектов, которые действительно любят то, чем занимаются...</p>
          <p class="feedback__secondline-continue5">Читать далее</p>
        </div>
      </div>
      <div class="feedback__content-thirdline">
        <div class="feedback__thirdline-card6">
          <img class="user-photo6" src="@/img/user-photo6.jpg" alt="user-photo">
          <h5 class="feedback__thirdline-title6">Андрей Засорин</h5>
          <p class="feedback__thirdline-text6">Ребята всегда на высоте проводят подобные мероприятия. Самое главное – практическая составляющая, всё, что услышал, я смог реализовать в работе. Особенно был интересен материал о визуальной составляющей рассылок и все самые топовые фишки в вёрстке писем...</p>
          <p class="feedback__thirdline-continue6">Читать далее</p>
        </div>
        <div class="feedback_content-add">
          <div class="feedback-add">
            <div class="add-horizontal"></div>
            <img class="vertical-border" src="@/img/vertical-border.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

  .feedback__content-firstline {
    display: flex;
  }

  .feedback__content-secondline {
    display: flex;
  }

  .feedback__content-thirdline {
    display: flex;
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
    padding-top: 170px;
  }

  .feedback__firstline-card1 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    width: 640px;
    height: 350px;
    margin: 48px 32px 32px 0;
    .feedback__firstline-title1 {
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
    .feedback__firstline-text1 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      width: 580px;
      margin-left: 32px;
      margin-top: 52px;
    }
    .feedback__firstline-continue1 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 124px;
      margin-left: 32px;
      margin-top: 56px;
      margin-bottom: 30px;
    }
    .user-photo1 {
      border-radius: 100px;
      margin-top: 30px;
      margin-left: 30px;
    }
  }

  .feedback__firstline-card2 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;

    width: 448px;
    height: 350px;
    margin-top: 48px;
    margin-bottom: 32px;
    .user-photo2 {
      border-radius: 100px;
      margin-top: 30px;
      margin-left: 30px;
    }
    .feedback__firstline-title2 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      color: #404040;

      width: 144px;
      margin-left: 137px;
      margin-top: -65px;
    }
    .feedback__firstline-text2 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      padding-top: 52px;
      padding-left: 32px;
      width: 400px;
    }
    .feedback__firstline-continue2 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 160px;
      padding-left: 32px;
      padding-top: 32px;
    }
  }

  .feedback__secondline-card3 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;

    width: 352px;
    height: 350px;

    margin-bottom: 32px;
    .user-photo3 {
      border-radius: 100px;
      margin-top: 30px;
      margin-left: 30px;
    }
    .feedback__secondline-title3 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      color: #404040;

      width: 144px;
      margin-left: 137px;
      margin-top: -65px;
    }
    .feedback__secondline-text3 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      padding-top: 52px;
      padding-left: 32px;
      width: 320px;
    }
    .feedback__secondline-continue3 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 160px;
      padding-left: 32px;
      padding-top: 56px;
    }
  }

  .feedback__secondline-card4 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;

    width: 352px;
    height: 350px;

    margin-left: 32px;
    margin-bottom: 32px;
    .user-photo4 {
      margin-top: 30px;
      margin-left: 30px;
      width: 80px;
      height: 80px;
    }
    .feedback__secondline-title4 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      color: #404040;

      width: 144px;
      margin-left: 137px;
      margin-top: -65px;
    }
    .feedback__secondline-text4 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      padding-top: 52px;
      padding-left: 32px;
      width: 320px;
    }
    .feedback__secondline-continue4 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 160px;
      padding-left: 32px;
      padding-top: 32px;
    }
  }

  .feedback__secondline-card5 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;

    width: 352px;
    height: 350px;

    margin-left: 32px;
    margin-bottom: 32px;
    .user-photo5 {
      margin-top: 30px;
      margin-left: 30px;
      width: 80px;
      height: 80px;
    }
    .feedback__secondline-title5 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      color: #404040;

      width: 144px;
      margin-left: 137px;
      margin-top: -65px;
    }
    .feedback__secondline-text5 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      padding-top: 52px;
      padding-left: 32px;
      width: 320px;
    }
    .feedback__secondline-continue5 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 160px;
      padding-left: 32px;
      padding-top: 32px;
    }
  }

  .feedback__thirdline-card6 {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    width: 640px;
    height: 350px;

    margin-bottom: 180px;
    .feedback__thirdline-title6 {
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
    .feedback__thirdline-text6 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;

      color: #1A1A1A;

      width: 580px;
      margin-left: 32px;
      margin-top: 52px;
    }
    .feedback__thirdline-continue6 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 18px;
      line-height: 22px;

      color: #0CB27F;

      width: 124px;
      margin-left: 32px;
      margin-top: 56px;
      margin-bottom: 30px;
    }
    .user-photo6 {
      border-radius: 100px;
      margin-top: 30px;
      margin-left: 30px;
    }
  }

  .feedback_content-add {
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;

    width: 448px;
    height: 350px;

    margin-left: 32px;
    margin-bottom: 180px;
    .feedback-add {
      background: #F9F9F9;
      border-radius: 8px;

      width: 172px;
      height: 172px;

      margin: 89px 138px;
      position: relative;
      .add-horizontal {
        border-bottom: 2px solid #C7C7C7;
        width: 125px;

        margin-left: 24px;
        padding-top: 86px;
      }
      .vertical-border {
        margin-left: 86px;
        top: 25px;
        position: absolute;
      }
    }
  }
</style>