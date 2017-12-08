<template>
  <header>
    <img class="logo" src="./assets/logo.png"/>
    <img class="triangles" src="./assets/triangles.png"/>
    <div class="main-text text-white">
      <span style="font-style: italic; font-weight: bold">
        <span class="with-border">Стр</span><span>ельнёт!</span>
      </span>
      <div style="margin-top: .94vw">
        <span>Увеличим поток клиентов в ваш бизнес на 30-50% за несколько месяцев!</span>
      </div>
    </div>
    <div class="contacts-messangers">
      <img class="messangers" src="./assets/messangers.png"/>
      <div class="contacts">
        <div class="contact">
          <img class="icon" src="./assets/velcom.png">
          <span>+375 (29) 348-91-27</span>
        </div>
        <div class="contact">
          <img class="icon" src="./assets/mts.png">
          <span>+375 (33) 664-71-74</span>
        </div>
        <div class="contact">
          <img class="icon" src="./assets/e-mail.png">
          <span>igor.delovoy@gmail.com</span>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
  export default {
    name: 'Header'
  }
</script>

<style lang="scss" scoped>
  header {
    width: 100%;
    padding-bottom: 4.73vw;
    background-image: url("./assets/header-background.png");
    background-size: cover;
    .triangles {
      width: 100%;
    }
    .logo {
      position: absolute;
      top: 2.9vw;
      left: 3.9vw;
      height: 3.52vw;
    }
    .main-text {
      line-height: 1.15;
      position: absolute;
      top: 14.6vw;
      left: 18vw;
      width: 32.6vw;
      font-size: 2.5vw;
      .with-border {
        padding-bottom: .52vw;
        border-bottom: solid white 1px;
      }
    }
    .contacts-messangers {
      position: absolute;
      top: 3.1vw;
      left: 77vw;
      display: inline-block;
      $k: 1vw * 1.2;
      .messangers {
        float: left;
        height: 1.68 * $k;
      }
      .contacts {
        float: left;
        margin-left: .63 * $k;
        .contact {
          display: flex;
          align-items: flex-start;
          color: white;
          font-weight: bold;
          font-size: .84 * $k;
          margin-bottom: .63 * $k;
          .icon {
            margin-right: .63 * $k;
            height: 1.68 * $k;
          }
        }
      }
    }
  }
</style>
