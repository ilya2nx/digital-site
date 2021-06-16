<template>
  <div class="learning-formats">
    <div class="container">
      <h2 class="title">ФОРМАТЫ ОБУЧЕНИЯ</h2>
      <div class="online">
        <h3 class="subtitle__online">Онлайн</h3>
        <p class="subtitle__online-text">Минимальные затраты времени и финансов. Вам не придется никуда ездить, вы можете пройти онлайн- курс в комфортном для вас режиме и вернуться  к учебным материалам в любое время — доступ  к курсу бессрочный.</p>
        <p class="online-link">Базовый курс по емейл-маркетингу</p>
        <img class="online-image" src="@/img/online-image.jpg" alt="online">
      </div>
      <div class="offline">
        <h3 class="subtitle__offline">Оффлайн</h3>
        <p class="subtitle__offline-text">Интенсивные занятия, живое общение с наставниками и другими учениками, актуальные тренды и вечные вопросы. Оффлайн-курсы позволят узнать максимум <br /> в сжатые сроки.</p>
        <p class="offline-link1">Цифровой маркетинг</p>
        <p class="offline-link2">CRM - маркетинг</p>
        <p class="offline-link3">Digital team</p>
        <img class="offline-image" src="@/img/offline-image.jpg" alt="offline">
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .title {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 34px;
    line-height: 41px;
    text-transform: uppercase;

    color: #335381;

    padding-top: 160px;
  }
  
  .online {
    position: relative;
    .subtitle__online {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 22px;
      line-height: 27px;

      color: #0CB27F;

      padding-top: 42px;
    }
    .subtitle__online-text {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 26px;

      color: #404040;
      
      padding-top: 24px;
      max-width: 530px;
    }
    .online-link {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      text-transform: uppercase;

      color: #404040;

      padding-top: 35px;

      border-bottom: solid 1px #404040;
      padding-bottom: 7px;
      max-width: 407px;
    }
    .online-image {
      position: absolute;
      right: 0;
      bottom: -93px;
    }
  }

  .offline {
    position: relative;
    .subtitle__offline {
      position: absolute;

      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 22px;
      line-height: 27px;

      color: #0CB27F;

      padding-top: 204px;
      right: 428px;
    }
    .subtitle__offline-text {
      position: absolute;

      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 26px;

      color: #404040;

      right: 0;
      padding-top: 255px;
      max-width: 540px;
    }
    .offline-link1 {
      position: absolute;

      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      text-transform: uppercase;

      color: #404040;

      padding-top: 394px;
      right: 297px;

      border-bottom: solid 1px #404040;
      padding-bottom: 7px;
      max-width: 244px;
    }
    .offline-link2 {
      position: absolute;

      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      text-transform: uppercase;

      color: #404040;

      padding-top: 394px;
      right: 70px;

      border-bottom: solid 1px #404040;
      padding-bottom: 7px;
      max-width: 181px;
    }
    .offline-link3 {
      position: absolute;

      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 22px;

      text-transform: uppercase;

      color: #404040;

      padding-top: 454px;
      right: 408px;

      border-bottom: solid 1px #404040;
      padding-bottom: 7px;
      max-width: 181px;
    }
    .offline-image {
      padding-top: 200px;
      padding-left: 5px;
    }
  }

  @media (max-width: 900px) {
    .title {
      font-size: 26px;
      line-height: 32px;
      padding-top: 90px;
    }

    .online {
      .subtitle__online {
        font-size: 16px;
        line-height: 20px;
        padding-top: 24px;
      }
      .online-image {
        width: 328px;
        height: 248px;
        bottom: 0;
      }
      .subtitle__online-text {
        font-size: 14px;
        line-height: 18px;
        max-width: 320px;
      }
      .online-link {
        font-size: 16px;
        line-height: 20px;
        max-width: 244px;
        padding-top: 32px;
      }
    }

    .offline {
      .subtitle__offline {
        font-size: 16px;
        line-height: 20px;
        padding-top: 100px;
        right: 228px;
      }
      .offline-image {
        width: 341px;
        padding-top: 93px;
        padding-left: 0;
        bottom: 0;
      }
      .subtitle__offline-text {
        font-size: 14px;
        line-height: 18px;
        right: -18px;
        padding-top: 151px;
        max-width: 328px;
      }
      .offline-link1 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 265px;
        right: 95px;

        padding-bottom: 5px;
        max-width: 217px;
      }
      .offline-link2 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 315px;
        right: 150px;

        padding-bottom: 5px;
        max-width: 161px;
      }
      .offline-link3 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 315px;
        right: 0px;

        padding-bottom: 5px;
        max-width: 119px;
      }
    }
  }

  @media (max-width: 320px) {
    .title {
      font-size: 22px;
      line-height: 27px;
      padding-top: 55px;
      padding-left: 7px;
    }

    .online {
      .subtitle__online {
        font-size: 16px;
        line-height: 20px;
        padding-top: 300px;
      }
      .online-image {
        width: 328px;
        height: 248px;
        bottom: 0;
        top: 24px;
        right: -10px;
      }
      .subtitle__online-text {
        font-size: 14px;
        line-height: 18px;
        max-width: 270px;
      }
      .online-link {
        font-size: 16px;
        line-height: 20px;
        max-width: 244px;
        padding-top: 24px;
      }
    }

    .offline {
      .subtitle__offline {
        font-size: 16px;
        line-height: 20px;
        padding-top: 300px;
        right: 210px;
      }
      .offline-image {
        width: 320px;
        height: 253px;
        padding-top: 50px;
        padding-left: 0;
        margin-left: -10px;
      }
      .subtitle__offline-text {
        font-size: 14px;
        line-height: 18px;
        right: 6px;
        padding-top: 330px;
        max-width: 287px;
      }
      .offline-link1 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 465px;
        right: 77px;

        padding-bottom: 5px;
        max-width: 217px;
      }
      .offline-link2 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 520px;
        right: 133px;

        padding-bottom: 5px;
        max-width: 161px;
      }
      .offline-link3 {
        font-size: 16px;
        line-height: 20px;
        padding-top: 575px;
        right: 175px;

        padding-bottom: 5px;
        max-width: 119px;
      }
    }
  }
</style>