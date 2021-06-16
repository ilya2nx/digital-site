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
          <div class="gradient"></div>
          <div class="dots"></div>
          <div class="band"></div>
          <div class="container">
            <div class="numbers">
              <p class="number">140</p>
              <p class="number">10</p>
              <p class="number">30%</p>
            </div>
            <div class="numbers-text">
              <p class="text-1">человек обучилось на наших курсах</p>
              <p class="text-2">городов</p>
              <p class="text-3">слушателей курсов возвращаются к нам снова</p>
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
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
  }

  .container-second {
    position: relative;
    max-height: 170px;
    z-index: -4;
    .gradient {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/gradient-numbers.png') center center / cover no-repeat;
      z-index: -3;
    }
    .dots {
      background: url('../img/dots-numbers.png') center center / cover no-repeat;
      background-size: auto;
      z-index: -1;
      position: absolute;
      height: 100%;
      width: 100%;
      max-width: 1300px;
      left: -30px;
      right: 0;
      margin: auto;
    }
    .band {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/band-numbers.png') center center / cover no-repeat;
      z-index: -2;
    }
    .container {
      position: relative;
      top: -60px;
    }
  }

  .numbers {
    display: flex;
    justify-content: space-between;
    margin-left: 90px;
    margin-right: 70px;
    text-shadow: -6px 0px 0px rgba(128, 128, 128, 0.2);
    .number {
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
    .number:nth-child(2) {
      margin-left: 245px;
      margin-right: 227px;
    }
  }

  .numbers-text {
      display: flex;
      justify-content: space-between;
    .text-1,.text-2,.text-3 {
      font-family: 'Montserrat', sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 22px;
      line-height: 27px;
      text-align: center;

      color: white;

      margin-top: 4px;
    }
    .text-1 {
      max-width: 235px;
      margin-left: 60px;
      margin-bottom: 55px;
    }
    .text-2 {
      max-width: 97px;
      margin-left: 219px;
      margin-right: 177px;
      margin-bottom: 82px;
    }
    .text-3 {
      max-width: 319px;
      margin-right: 10px;
      margin-bottom: 55px;
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
      width: 380px;
      height: 36px;
      padding-bottom: 130px;
      margin-top: 16px;
    }

    .container-second {
      max-height: 124px;
      .gradient {
        background: url('../img/gradient-numbers-ipad.png') center center / cover no-repeat;
      }
      .band {
        background: url('../img/band-numbers-ipad.png') center center / cover no-repeat;
      }
      .dots {
        background: url('../img/dots-numbers-ipad.png') center center / cover no-repeat;
        max-width: 900px;
        left: 0;
      }
      .container {
        top: -40px;
      }
    }

    .numbers {
      margin-left: 52px;
      .number {
        font-size: 64px;
        line-height: 64px;
      }
      .number:nth-child(2) {
        margin-left: 140px;
        margin-right: 129px;
      }
    }

    .numbers-text {
      .text-1,.text-2,.text-3 {
        font-size: 16px;
        line-height: 20px;
        margin-top: 9px;
      }
      .text-1 {
        max-width: 171px;
        margin-left: 20px;
        margin-bottom: 55px;
      }
      .text-2 {
        max-width: 71px;
        margin-left: 113px;
        margin-right: 85px;
        margin-bottom: 82px;
      }
      .text-3 {
        max-width: 212px;
        margin-right: 5px;
        margin-bottom: 55px;
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
      max-height: 426px;
      .gradient {
        background: url('../img/gradient-numbers-phone.png') center center / cover no-repeat;
      }
      .dots {
        background: url('../img/dots-numbers-phone.png') center center / cover no-repeat;
        max-width: 320px;
        left: 0;
      }
      .container {
        top: -40px;
      }
    }

    .numbers {
      margin-left: 76px;
      flex-direction: column;
      .number {
        font-size: 64px;
        line-height: 64px;
        margin-bottom: 94px;
      }
      .number:nth-child(2) {
        margin-left: 0px;
        margin-right: 0px;
        margin-bottom: 70px;
      }
    }

    .numbers-text {
      flex-direction: column;
      .text-1,.text-2,.text-3 {
        font-size: 16px;
        line-height: 20px;
        margin-top: 9px;
      }
      .text-1 {
        max-width: 171px;
        margin-left: 65px;
        margin-bottom: 110px;
        margin-top: -380px;
      }
      .text-2 {
        max-width: 71px;
        margin-left: 115px;
        margin-bottom: 115px;
      }
      .text-3 {
        max-width: 212px;
        margin-left: 40px;
        margin-bottom: 55px;
      }
    }
  }
</style>
