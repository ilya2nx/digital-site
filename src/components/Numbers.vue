<template>
  <div class="digital-numbers">
    <div class="container">
      <h2 class="title">DIGITAL В ЦИФРАХ</h2>
      <p class="subtitle">Мы стремимся к развитию и расширению границ. 
        И у нас получается.
      </p>
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

    text-align: center;

    color: #404040;

    margin-top: 33px;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
  }

  .numbers {
    display: flex;
    justify-content: space-between;
    padding-top: 96px;
    margin-left: 90px;
    margin-right: 70px;
    text-shadow: -6px 0px 0px rgb(230, 230, 230);
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

      color: #000000;

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
</style>
