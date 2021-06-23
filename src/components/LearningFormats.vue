<template>
  <div class="learning-formats">
    <div class="container">
      <h2 class="title">ФОРМАТЫ ОБУЧЕНИЯ</h2>
      <div class="online">
        <div class="online-content">
          <h3 class="subtitle__online">Онлайн</h3>
          <p class="subtitle__online-text">Минимальные затраты времени и финансов. Вам не придется никуда ездить, вы можете пройти онлайн- курс в комфортном для вас режиме и вернуться  к учебным материалам в любое время — доступ  к курсу бессрочный.</p>
          <div class="link"><a href="#" class="online-link">Базовый курс по емейл-маркетингу</a></div>
        </div>
        <div class="image-container">
          <img class="online-image" src="@/img/online-image.jpg" alt="online">
        </div>
      </div>
      <div class="offline">
        <div class="image-container">
          <img class="offline-image" src="@/img/offline-image.jpg" alt="offline">
        </div>
        <div class="offline-content">
          <h3 class="subtitle__offline">Оффлайн</h3>
          <p class="subtitle__offline-text">Интенсивные занятия, живое общение с наставниками и другими учениками, актуальные тренды и вечные вопросы. Оффлайн-курсы позволят узнать максимум <br /> в сжатые сроки.</p>
          <div class="links">
            <div class="half"><a href="#" class="offline-link">Цифровой маркетинг</a></div>
            <div class="half"><a href="#" class="offline-link">CRM - маркетинг</a></div>
            <div class="only"><a href="#" class="offline-link">Digital team</a></div>
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
  a {
    text-decoration: none;
  }

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
    display: flex;
    justify-content: space-between;
    .online-content {
      width: 50%;
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
        width: 89%;
      }
      .link {
        padding-top: 35px;
        border-bottom: solid 1px #404040;
        padding-bottom: 7px;
        width: 73%;
      }
      .online-link {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 22px;
  
        text-transform: uppercase;
  
        color: #404040;
      }
    }
    .image-container {
      display: flex;
      width: 45%;
      .online-image {
        padding-top: 35px;
        width: 100%;
      }
    }
  }

  .offline {
    display: flex;
    justify-content: space-between;
    .offline-content {
      width: 48%;
      .subtitle__offline {
  
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 22px;
        line-height: 27px;
  
        color: #0CB27F;
  
        padding-top: 100px;
      }
      .subtitle__offline-text {
  
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 26px;
  
        color: #404040;
  
        padding-top: 24px;
        width: 100%;
      }
      .links {
        display: flex;
        flex-wrap: wrap;
        div {
          padding-bottom: 7px;
        }
        .half {
          border-bottom: solid 1px #404040;
          margin-right: 44px;
          padding-top: 35px;
        }
        .only {
          border-bottom: solid 1px #404040;
          padding-top: 30px;
        }
        .offline-link {
    
          font-family: 'Montserrat', sans-serif;
          font-style: normal;
          font-weight: 600;
          font-size: 18px;
          line-height: 22px;
    
          text-transform: uppercase;
    
          color: #404040;
    
        }
      }
    }
    .image-container {
      display: flex;
      width: 45%;
      .offline-image {
        padding-top: 100px;
        width: 100%;
      }
    }
  }

  @media (max-width: 900px) {
    .title {
      font-size: 26px;
      line-height: 32px;
      padding-top: 90px;
    }

    .online {
      display: flex;
      justify-content: space-between;
      .online-content {
        width: 55%;
        .subtitle__online {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__online-text {
          font-size: 14px;
          line-height: 18px;          
          padding-top: 16px;
          width: 89%;
        }
        .link {
          padding-top: 32px;
          border-bottom: solid 1px #404040;
          padding-bottom: 7px;
          width: 73%;
        }
        .online-link {
          font-size: 16px;
          line-height: 20px;
        }
      }
      .image-container {
        display: flex;
        width: 45%;
        .online-image {
          padding-top: 35px;
          width: 100%;
        }
      }
    }

    .offline {
      display: flex;
      justify-content: space-between;
      .offline-content {
        width: 48%;
        .subtitle__offline {
          font-size: 16px;
          line-height: 20px;
        }
        .subtitle__offline-text {
          font-size: 14px;
          line-height: 18px;    
          padding-top: 31px;
          width: 100%;
        }
        .links {
          display: flex;
          flex-wrap: wrap;
          div {
            padding-bottom: 7px;
          }
          .half {
            border-bottom: solid 1px #404040;
            margin-right: 22px;
            padding-top: 25px;
          }
          .only {
            border-bottom: solid 1px #404040;
            padding-top: 25px;
          }
          .offline-link {
            font-size: 16px;
            line-height: 20px;
          }
        }
      }
      .image-container {
        display: flex;
        width: 45%;
        .offline-image {
          padding-top: 100px;
          width: 100%;
        }
      }
    }
  }

  @media (max-width: 630px) {
    .title {
      font-size: 26px;
      line-height: 32px;
      padding-top: 90px;
    }

    .online {
      display: flex;
      justify-content: space-between;
      .online-content {
        width: 45%;
        .subtitle__online {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__online-text {
          font-size: 14px;
          line-height: 16px;          
          padding-top: 10px;
          width: 89%;
        }
        .link {
          padding-top: 22px;
          border-bottom: solid 1px #404040;
          padding-bottom: 7px;
          width: 73%;
        }
        .online-link {
          font-size: 14px;
          line-height: 18px;
        }
      }
      .image-container {
        display: flex;
        width: 55%;
        .online-image {
          padding-top: 35px;
          width: 100%;
          height: 250px;
        }
      }
    }

    .offline {
      display: flex;
      justify-content: space-between;
      .offline-content {
        width: 45%;
        .subtitle__offline {
          font-size: 16px;
          line-height: 20px;
        }
        .subtitle__offline-text {
          font-size: 14px;
          line-height: 16px;    
          padding-top: 31px;
          width: 100%;
        }
        .links {
          display: flex;
          flex-wrap: wrap;
          div {
            padding-bottom: 5px;
          }
          .half {
            border-bottom: solid 1px #404040;
            margin-right: 12px;
            padding-top: 15px;
          }
          .only {
            border-bottom: solid 1px #404040;
            padding-top: 15px;
          }
          .offline-link {
            font-size: 14px;
            line-height: 18px;
          }
        }
      }
      .image-container {
        display: flex;
        width: 50%;
        .offline-image {
          padding-top: 100px;
          width: 100%;
          height: 300px;
        }
      }
    }
  }

  @media (max-width: 425px) {
    .title {
      font-size: 22px;
      line-height: 27px;
      padding-top: 55px;
    }

    .online {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .online-content {
        width: 100%;
        order: 2;
        .subtitle__online {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__online-text {
          font-size: 14px;
          line-height: 18px;          
          padding-top: 16px;
          width: 89%;
        }
        .link {
          padding-top: 32px;
          border-bottom: solid 1px #404040;
          padding-bottom: 7px;
          width: 82%;
        }
        .online-link {
          font-size: 16px;
          line-height: 20px;
        }
      }
      .image-container {
        display: flex;
        width: 100%;
        order: 1;
        .online-image {
          padding-top: 24px;
          width: 100%;
          height: unset;
        }
      }
    }

    .offline {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .offline-content {
        width: 100%;
        .subtitle__offline {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__offline-text {
          font-size: 14px;
          line-height: 18px;    
          padding-top: 31px;
          width: 100%;
        }
        .links {
          display: flex;
          flex-wrap: wrap;
          div {
            padding-bottom: 7px;
          }
          .half {
            border-bottom: solid 1px #404040;
            margin-right: 22px;
            padding-top: 25px;
          }
          .only {
            border-bottom: solid 1px #404040;
            padding-top: 25px;
          }
          .offline-link {
            font-size: 16px;
            line-height: 20px;
          }
        }
      }
      .image-container {
        display: flex;
        width: 100%;
        .offline-image {
          padding-top: 100px;
          width: 100%;
          height: unset;
        }
      }
    }
  }

  @media (max-width: 320px) {
    .title {
      font-size: 22px;
      line-height: 27px;
      padding-top: 55px;
    }

    .online {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .online-content {
        width: 100%;
        order: 2;
        .subtitle__online {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__online-text {
          font-size: 14px;
          line-height: 18px;          
          padding-top: 16px;
          width: 89%;
        }
        .link {
          padding-top: 32px;
          border-bottom: solid 1px #404040;
          padding-bottom: 7px;
          width: 82%;
        }
        .online-link {
          font-size: 16px;
          line-height: 20px;
        }
      }
      .image-container {
        display: flex;
        width: 100%;
        order: 1;
        .online-image {
          padding-top: 24px;
          width: 100%;
          height: unset;
        }
      }
    }

    .offline {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .offline-content {
        width: 100%;
        .subtitle__offline {
          font-size: 16px;
          line-height: 20px;
          padding-top: 24px;
        }
        .subtitle__offline-text {
          font-size: 14px;
          line-height: 18px;    
          padding-top: 31px;
          width: 100%;
        }
        .links {
          display: flex;
          flex-wrap: wrap;
          div {
            padding-bottom: 7px;
          }
          .half {
            border-bottom: solid 1px #404040;
            margin-right: 22px;
            padding-top: 25px;
          }
          .only {
            border-bottom: solid 1px #404040;
            padding-top: 25px;
          }
          .offline-link {
            font-size: 16px;
            line-height: 20px;
          }
        }
      }
      .image-container {
        display: flex;
        width: 100%;
        .offline-image {
          padding-top: 100px;
          width: 100%;
          height: unset;
        }
      }
    }
  }
</style>