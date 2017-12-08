<template>
  <footer class="footer">
    <div class="block contacts">
      <h4 class="header">
        Наши контакты
      </h4>
      <div class="main">
        <div class="contact">
          <img src="./assets/footer/mts.png" class="icon">
          <span>+375 (33) 664-71-74</span>
        </div>
        <div class="contact">
          <img src="./assets/footer/velcom.png" class="icon">
          <span>+375 (29) 348-91-27</span>
        </div>
        <div class="contact">
          <img src="./assets/footer/e-mail.png" class="icon">
          <span>igor.delovoy@gmail.com</span>
        </div>
        <div class="contact">
          <img src="./assets/footer/placeholder.png" class="icon">
          <span>г. Минск, ул. Камайская 10</span>
        </div>
      </div>
    </div>
    <div class="block social-messangers-container">
      <div class="social">
        <h4 class="header">
          Мы в социальных сетях
        </h4>
        <div class="main">
          <img src="./assets/footer/Facebook.png" class="icon">
          <img src="./assets/footer/Instagram.png" class="icon">
          <img src="./assets/footer/Twitter.png" class="icon">
          <img src="./assets/footer/GooglePlus.png" class="icon">
          <img src="./assets/footer/Tumblr.png" class="icon">
        </div>
      </div>
      <div class="messangers">
        <h4 class="header">Мессенджеры</h4>
        <div class="main">
          <img src="./assets/footer/messangers.png" class="icon">
          <span>+375 (29) 348-91-27</span>
        </div>
      </div>
    </div>
    <div class="block reverse-call">
      <h4 class="header">Обратный звонок</h4>
      <div class="main">
        <form>
          <input type="text" placeholder="Имя">
          <input type="text" placeholder="Номер телефона">
          <input type="text" placeholder="Удобное время для звонка">
          <button class="button blue">ЗАКАЗАТЬ ЗВОНОК</button>
          <div class="or">или</div>
          <button class="button red">ПОЗВОНИТЬ ОНЛАЙН</button>
          <div class="get-for-free">*это бесплатно</div>
        </form>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'Footer'
  }
</script>

<style lang="scss" scoped>
  .footer {
    background-image: url("./assets/footer-backgrong.png");
    background-size: cover;
    height: 29.3vw;
    padding: 2.78vw 6.95vw 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    color: white;
    .header {
      margin-bottom: 2.4vw;
    }
    .block {
      height: 70%;
    }
    .contacts {
      .header {
        margin-bottom: 3.1vw;
      }
      .main {
        height: 70%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        .contact {
          .icon {
            margin-right: .94vw;
          }
        }
      }
    }
    .social-messangers-container {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      .social {
        .main {
          display: flex;
          justify-content: space-between;
          width: 18vw;
          .icon {
            height: 2.1vw;
          }
        }
      }
      .messangers {
        .main {
          display: flex;
          justify-content: space-between;
          align-items: center;
          width: 18vw;
          .icon {
            height: 2.1vw;
          }
        }
      }
    }
    .reverse-call {
      width: 16.2vw;
      input {
        width: 100%;
        border-radius: 17px;
        border: solid 1px #a4a4a4;
        background: none;
        margin-bottom: .84vw;
        color: #a4a4a4;
        font-size: .9vw;
        padding: 0 1.68vw;
        line-height: 1.89vw;
      }
      button {
        width: 100%;
        height: 2.6vw;
        border-radius: 25px;
        color: white;
        font-weight: 600;
        font-size: small;
        border: none;
        &:hover {
          cursor: pointer;
        }
        &.blue {
          margin-top: 1.57vw;
          background: #48578a;
        }
        &.red {
          background: #d03746;
        }
      }
      .or {
        line-height: 2.2vw;
        color: #a4a4a4;
        font-size: .9vw;
        text-align: center;
      }
      .get-for-free {
        text-align: right;
        color: #a4a4a4;
        font-size: .8vw;
        line-height: 2;
      }
    }
  }
</style>
