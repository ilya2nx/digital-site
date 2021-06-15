<template>
  <div class="partners">
    <div class="gradient"></div>
    <div class="green-dots"></div>
    <div class="band"></div>
    <div class="container">
      <div class="logo-firstline">
        <img class="abbyy-logo" src="@/img/abbyy-logo.png" alt="abbyy-logo">
        <img class="shoppinglive-logo" src="@/img/shoppinglive-logo.png" alt="shoppinglive-logo">
        <img class="henderson-logo" src="@/img/henderson-logo.png" alt="henderson-logo">
        <img class="mail-logo" src="@/img/mail-logo.png" alt="mail-logo">
        <img class="travelataru-logo" src="@/img/travelataru-logo.png" alt="travelataru-logo">
      </div>
      <div class="logo-secondline">
        <img class="dominospizza-logo" src="@/img/dominospizza-logo.png" alt="dominospizza-logo">
        <img class="leroymerlin-logo" src="@/img/leroymerlin-logo.png" alt="leroymerlin-logo">
        <img class="santehnikaonline-logo" src="@/img/santehnikaonline-logo.png" alt="santehnikaonline-logo">
        <img class="butik-logo" src="@/img/butik-logo.png" alt="butik-logo">
        <img class="fabrikaokon-logo" src="@/img/fabrikaokon-logo.png" alt="fabrikaokon-logo">
      </div>
      <div class="logo-thirdline">
        <img class="agentru-logo" src="@/img/agentru-logo.png" alt="agentru-logo">
        <img class="kinderly-logo" src="@/img/kinderly-logo.png" alt="kinderly-logo">
        <img class="profiru-logo" src="@/img/profiru-logo.png" alt="profiru-logo">
        <img class="citylink-logo" src="@/img/citylink-logo.png" alt="citylink-logo">
        <img class="xpcom-logo" src="@/img/xpcom-logo.png" alt="xpcom-logo">
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .partners {
    height: 417px;
    position: relative;
    .gradient {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/gradient-partners.png') center center / cover no-repeat;
      z-index: -3;
    }
    .green-dots {
      background: url('../img/dots-partners.png') center center / cover no-repeat;
      z-index: -1;
      position: absolute;
      height: 100%;
      width: 100%;
      max-width: 1300px;
      left: -20px;
      right: 0;
      margin: auto;
    }
    .band {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('../img/band-partners.png') center center / cover no-repeat;
      z-index: -2;
    }
  }
  
  .logo-firstline {
    display: flex;
    .abbyy-logo {
      margin-top: 94px;
      width: 108px;
      height: 32px;
    }
    .shoppinglive-logo {
      margin-top: 88px;
      margin-left: 108px;
      width: 98px;
      height: 43px;
    }
    .henderson-logo {
      margin-top: 91px;
      margin-left: 108px;
      width: 238px;
      height: 38px;
    }
    .mail-logo {
      margin-top: 94px;
      margin-left: 108px;
      width: 96px;
      height: 32px;
    }
    .travelataru-logo {
      margin-top: 85px;
      margin-left: 108px;
      width: 148px;
      height: 50px;
    }
  }

  .logo-secondline {
    display: flex;
    .dominospizza-logo {
      margin-top: 45px;
      width: 241px;
      height: 61px;
    }
    .leroymerlin-logo {
      margin-top: 50px;
      margin-left: 78px;
      width: 81px;
      height: 49px;
    }
    .santehnikaonline-logo {
      margin-top: 58px;
      margin-left: 78px;
      width: 223px;
      height: 35px;
    }
    .butik-logo {
      margin-top: 60px;
      margin-left: 78px;
      width: 142px;
      height: 30px;
    }
    .fabrikaokon-logo {
      margin-top: 50px;
      margin-left: 78px;
      width: 120px;
      height: 50px;
    }
  }

  .logo-thirdline {
    display: flex;
    .agentru-logo {
      margin-top: 50px;
      width: 200px;
      height: 36px;
    }
    .kinderly-logo {
      margin-top: 50px;
      margin-left: 86px;
      width: 148px;
      height: 36px;
    }
    .profiru-logo {
      margin-top: 55px;
      margin-left: 86px;
      width: 139px;
      height: 22px;
    }
    .citylink-logo {
      margin-top: 45px;
      margin-left: 86px;
      width: 187px;
      height: 46px;
    }
    .xpcom-logo {
      margin-top: 45px;
      margin-left: 86px;
      width: 103px;
      height: 44px;
    }
  }

</style>

