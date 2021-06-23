<template>
  <div class="digital-numbers">
      <div class="container-first">
        <div class="container">
          <h2 class="title">DIGITAL В ЦИФРАХ</h2>
          <p class="subtitle">Мы стремимся к развитию и расширению границ. 
            И у нас получается.
          </p>
        </div>
      </div>
        <div class="container-second">
          <div class="container">
            <div class="numbers">
              <div class="number">
                <p class="num">140</p>
                <p class="text">человек обучилось <br /> на наших курсах</p>
              </div>
              <div class="number">
                <p class="num">10</p>
                <p class="text">городов</p>
              </div>
              <div  class="number">
                <p class="num">30%</p>
                <p class="text">слушателей курсов возвращаются к нам снова</p>
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
  .title {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 34px;
    line-height: 41px;
    text-transform: uppercase;

    color: #335381;

    padding-top: 121px;
    max-width: 346px;
    margin-left: auto;
    margin-right: auto;
  }

  .subtitle {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 26px;
    padding-bottom: 155px;

    text-align: center;

    color: #404040;

    margin-top: 33px;
    width: 44%;
    margin-left: auto;
    margin-right: auto;
  }

  .container-second {
    position: relative;
    background-image: url('../img/numbers-background.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top center;
    .container {
      position: relative;
      top: -60px;
    }
  }

  .numbers {
    display: flex;
    // flex-wrap: wrap;
    justify-content: space-between;
    text-shadow: -6px 0px 0px rgba(128, 128, 128, 0.2);
    .number {
      width: 31%;
      .num {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: bold;
        font-size: 96px;
        line-height: 117px;

        text-align: center;
        letter-spacing: 0.02em;
        text-transform: uppercase;

        color: #40E896;
      }
      .text {
        font-family: 'Montserrat', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 22px;
        line-height: 27px;
        text-align: center;

        color: white;

        margin-top: 4px;
      }
    }
  }

  @media (max-width: 900px) {
    .title {
      font-size: 26px;
      line-height: 32px;
      padding-top: 75px;
      text-align: center;
    }
    
    .subtitle {
      font-size: 14px;
      line-height: 18px;
      width: 57%;
      height: 36px;
      padding-bottom: 130px;
      margin-top: 16px;
    }

    .container-second {
      height: 124px;
      position: relative;
      background-image: url('../img/numbers-background-ipad.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      background-position: top center;
      .container {
        position: relative;
        top: -40px;
      }
    }

    .numbers {
      .number {
        .num {
          width: 100%;
          font-size: 64px;
          line-height: 64px;
        }
        .num:nth-child(2) {
          margin-left: 140px;
          margin-right: 129px;
        }
        .text {
          font-size: 16px;
          line-height: 20px;
          margin-top: 9px;
        }
      }
    }
  }

  @media (max-width: 460px) {
    .title {
      font-size: 20px;
      line-height: 26px;
    }

    .subtitle {
      width: 50%;
    }

    .container-second {
      .container {
        top: -25px;
      }
    }

    .numbers {
      .number {
        .num {
          width: 100%;
          font-size: 40px;
          line-height: 40px;
        }
        .num:nth-child(2) {
          margin-left: 140px;
          margin-right: 129px;
        }
        .text {
          font-size: 12px;
          line-height: 16px;
          margin-top: 9px;
        }
      }
    }
  }

  @media (max-width: 320px) {
    .title {
      font-size: 22px;
      line-height: 27px;
      padding-top: 55px;
      width: 220px;
      text-align: center;
    }
    
    .subtitle {
      font-size: 14px;
      line-height: 18px;
      width: 199px;
      height: 54px;
      padding-bottom: 130px;
      margin-top: 16px;
    }

    .container-second {
      height: 426px;
      position: relative;
      background-image: url('../img/numbers-background-phone.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      background-position: top center;
      .container {
        position: relative;
        top: -40px;
      }
    }

    .numbers {
      flex-wrap: wrap;
      justify-content: space-between;
      height: 150px;
      .number {
        width: 100%;
        height: 100%;
        .num {
          font-size: 64px;
          line-height: 64px;
          margin-bottom: 9px;
        }
        .num:nth-child(2) {
          margin-left: 0px;
          margin-right: 0px;
          margin-bottom: 70px;
        }
        .text {
          font-size: 16px;
          line-height: 20px;
          margin-top: 9px;
        }
      }
    }
  }
</style>
