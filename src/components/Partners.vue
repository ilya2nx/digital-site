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

  @media (max-width: 900px) {
    .logo-firstline {
      .abbyy-logo {
        margin-top: 99px;
        width: 55px;
        height: 22px;
      }
      .shoppinglive-logo {
        margin-top: 93px;
        margin-left: 55px;
        width: 68px;
        height: 33px;
      }
      .henderson-logo {
        margin-top: 96px;
        margin-left: 55px;
        width: 138px;
        height: 28px;
      }
      .mail-logo {
        margin-top: 99px;
        margin-left: 55px;
        width: 76px;
        height: 22px;
      }
      .travelataru-logo {
        margin-top: 90px;
        margin-left: 55px;
        width: 108px;
        height: 40px;
      }
    }

    .logo-secondline {
      .dominospizza-logo {
        margin-top: 45px;
        width: 101px;
        height: 31px;
      }
      .leroymerlin-logo {
        margin-top: 50px;
        margin-left: 52px;
        width: 51px;
        height: 29px;
      }
      .santehnikaonline-logo {
        margin-top: 58px;
        margin-left: 52px;
        width: 123px;
        height: 20px;
      }
      .butik-logo {
        margin-top: 60px;
        margin-left: 52px;
        width: 102px;
        height: 20px;
      }
      .fabrikaokon-logo {
        margin-top: 50px;
        margin-left: 52px;
        width: 80px;
        height: 30px;
      }
    }

    .logo-thirdline {
      .agentru-logo {
        margin-top: 50px;
        width: 80px;
        height: 17px;
      }
      .kinderly-logo {
        margin-top: 50px;
        margin-left: 61px;
        width: 78px;
        height: 23px;
      }
      .profiru-logo {
        margin-top: 55px;
        margin-left: 61px;
        width: 89px;
        height: 15px;
      }
      .citylink-logo {
        margin-top: 55px;
        margin-left: 61px;
        width: 100px;
        height: 26px;
      }
      .xpcom-logo {
        margin-top: 45px;
        margin-left: 61px;
        width: 73px;
        height: 27px;
      }
    }
  }

  @media (max-width: 320px) {
    .partners {
      height: 438px;
      .gradient {
        background: url('../img/gradient-partners-phone.png') center center / cover no-repeat;
      }
      .green-dots {
        background: url('../img/dots-partners-phone.png') center center / cover no-repeat;
        max-width: 320px;
        left: 0;
      }
      .band {
        background: url('../img/band-partners-phone.png') center center / cover no-repeat;
      }
    }

    .logo-firstline {
      .abbyy-logo {
        margin-top: 99px;
        width: 108px;
        height: 32px;
        margin-left: 15px;
      }
      .shoppinglive-logo {
        margin-top: 93px;
        margin-left: 55px;
        width: 98px;
        height: 43px;
      }
      .henderson-logo {
        display: none;
      }
      .mail-logo {
        display: none;
      }
      .travelataru-logo {
        display: none;
      }
    }

    .logo-secondline {
      .dominospizza-logo {
        margin-top: 75px;
        width: 160px;
        height: 47px;
      }
      .leroymerlin-logo {
        margin-top: 60px;
        margin-left: 50px;
        width: 81px;
        height: 49px;
      }
      .santehnikaonline-logo {
        display: none;
      }
      .butik-logo {
        display: none;
      }
      .fabrikaokon-logo {
        display: none;
      }
    }

    .logo-thirdline {
      .agentru-logo {
        margin-top: 80px;
        width: 130px;
        height: 25px;
        margin-left: 15px;
      }
      .kinderly-logo {
        margin-top: 80px;
        margin-left: 35px;
        width: 100px;
        height: 28px;
      }
      .profiru-logo {
        display: none;
      }
      .citylink-logo {
        display: none;
      }
      .xpcom-logo {
        display: none;
      }
    }
  }

</style>

