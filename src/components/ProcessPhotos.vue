<template>
  <div class="process-photos">
    <div class="container">
      <h2 class="title">Как это было</h2>
      <div class="container__photos">
        <img class="item" src="@/img/photos/photo1.jpg" alt="photo1">
        <img class="item" src="@/img/photos/photo2.jpg" alt="photo2">
        <img class="item" src="@/img/photos/photo3.jpg" alt="photo3">
        <img class="item" src="@/img/photos/photo4.jpg" alt="photo4">
        <img class="item" src="@/img/photos/photo5.jpg" alt="photo5">
        <img class="item" src="@/img/photos/photo6.jpg" alt="photo6">
        <img class="item" src="@/img/photos/photo7.jpg" alt="photo7">
        <img class="item" src="@/img/photos/photo8.jpg" alt="photo8">
        <img class="item" src="@/img/photos/photo9.jpg" alt="photo9">
        <img class="item" src="@/img/photos/photo10.jpg" alt="photo10">
        <img class="item" src="@/img/photos/photo11.jpg" alt="photo11">
        <img class="item" src="@/img/photos/photo12.jpg" alt="photo12">
        <img class="item" src="@/img/photos/photo13.jpg" alt="photo13">
        <img class="item" src="@/img/photos/photo14.jpg" alt="photo14">
        <img class="item" src="@/img/photos/photo15.jpg" alt="photo15">
        <img class="item" src="@/img/photos/photo16.jpg" alt="photo16">
        <img class="item" src="@/img/photos/photo17.jpg" alt="photo17">
        <img class="item" src="@/img/photos/photo18.jpg" alt="photo18">
        <img class="item" src="@/img/photos/photo19.jpg" alt="photo19">
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
  
  .title {
    font-family: 'Montserrat', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 34px;
    line-height: 41px;
    text-align: center;
    text-transform: uppercase;

    color: #335381;

    padding-top: 150px;
    padding-bottom: 65px;
  }

  .container__photos {
    display: flex;
    flex-flow: column wrap;
    align-content: space-between;
    height: 1890px; 
  }

  .item {
    width: 32%;
    margin-bottom: 32px;
  }

  .item:nth-child(1) { order: 1; }
  .item:nth-child(2) { order: 2; margin-left: 32px;}
  .item:nth-child(3) { order: 3; margin-left: 32px;}
  .item:nth-child(4) { order: 1; }
  .item:nth-child(5) { order: 2; margin-left: 32px;}
  .item:nth-child(6) { order: 3; margin-left: 32px;}
  .item:nth-child(7) { order: 1; }
  .item:nth-child(8) { order: 2; margin-left: 32px;}
  .item:nth-child(9) { order: 3; margin-left: 32px;}
  .item:nth-child(10) { order: 2; margin-left: 32px;}
  .item:nth-child(11) { order: 3; margin-left: 32px;}
  .item:nth-child(12) { order: 1; }
  .item:nth-child(13) { order: 2; margin-left: 32px;}
  .item:nth-child(14) { order: 1; }
  .item:nth-child(15) { order: 2; margin-left: 32px;}
  .item:nth-child(16) { order: 3; margin-left: 32px;}
  .item:nth-child(17) { order: 1; }
  .item:nth-child(18) { order: 2; margin-left: 32px;}
  .item:nth-child(19) { order: 3; margin-left: 32px;}

  .container__photos::before,
  .container__photos::after {
    content: "";
    flex-basis: 100%;
    width: 0;
    order: 2;
  }

  .position-btn {
    display: flex;
    justify-content: center;
    margin-bottom: 160px;
    .btn {
      border: none;
      border-radius: 2px;

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

</style>