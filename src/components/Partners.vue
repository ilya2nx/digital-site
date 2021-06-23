<template>
  <div class="partners">
    <div class="container">
      <div class="container-logo">
        <img class="abbyy-logo" src="@/img/abbyy-logo.png" alt="abbyy-logo">
        <img class="shoppinglive-logo" src="@/img/shoppinglive-logo.png" alt="shoppinglive-logo">
        <img class="henderson-logo" src="@/img/henderson-logo.png" alt="henderson-logo">
        <img class="mail-logo" src="@/img/mail-logo.png" alt="mail-logo">
        <img class="travelataru-logo" src="@/img/travelataru-logo.png" alt="travelataru-logo">           
        <img class="dominospizza-logo" src="@/img/dominospizza-logo.png" alt="dominospizza-logo">
        <img class="leroymerlin-logo" src="@/img/leroymerlin-logo.png" alt="leroymerlin-logo">
        <img class="santehnikaonline-logo" src="@/img/santehnikaonline-logo.png" alt="santehnikaonline-logo">
        <img class="butik-logo" src="@/img/butik-logo.png" alt="butik-logo">
        <img class="fabrikaokon-logo" src="@/img/fabrikaokon-logo.png" alt="fabrikaokon-logo">              
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
    background: url('../img/partners-background.jpg') center center / cover no-repeat;
    .container, .container-logo {
      height: 100%;
    }
    .container-logo {
      padding: 25px;
    }
  }
  
  .container-logo {
    display: flex;
    flex-wrap: wrap;
    position: relative;
    width: 100%;
    
    img {
      width: 20%;
      object-fit: scale-down;
    }
  }

  @media (max-width: 900px){
    .partners {
      height: 100%;
    }
    .container-logo img {
      padding: 20px;
      width: 33%;
    }
  }

  @media (max-width: 320px) {
    .partners {
      background-image: url('../img/partners-background-phone.jpg') center center / cover no-repeat;
      .container-logo img {
        padding: 10px;
        width: 50%;
      }
    }
  }

</style>

