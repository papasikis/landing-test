<template>
  <div class="suggestions row">
    <h2 class="header col-12">
      Что мы предлагаем
    </h2>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          Анализ бизнеса
        </h5>
        <div class="main-text">
          Проанализируем ситуацию, разработаем план по эффективному продвижению бизнеса в интернет и поможем воплотить его в жизнь!
        </div>
        <div class="footer-image">
          <img src="./assets/1-1.png">
        </div>
      </div>
    </div>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          Целевая аудитория
        </h5>
        <div class="main-text">
          Выявим Вашу целевую аудиторию и способы её эффективного привлечения
        </div>
        <div class="footer-image">
          <img src="./assets/1-2.png">
        </div>
      </div>
    </div>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          Сильные стороны
        </h5>
        <div class="main-text">
          Найдём сильные стороны и смыслы Вашего бизнеса или мероприятия. Составим Уникальное продающее предложение (оффер)!
        </div>
        <div class="footer-image">
          <img src="./assets/1-3.png">
        </div>
      </div>
    </div>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          SMM-продвижение
        </h5>
        <div class="main-text">
          Проанализируем ситуацию, разработаем план по эффективному продвижению бизнеса в Интернет и поможем воплотить его в жизнь!
        </div>
        <div class="footer-image">
          <img src="./assets/1-4.png">
        </div>
      </div>
    </div>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          Настройка рекламы
        </h5>
        <div class="main-text">
          Выявим Вашу целевую аудиторию и способы её эффективного привлечения
        </div>
        <div class="footer-image">
          <img src="./assets/1-5.png">
        </div>
      </div>
    </div>
    <div class="col-xl-4 col-lg-6">
      <div class="suggestion">
        <h5 class="header">
          Креатив
        </h5>
        <div class="main-text">
          Найдём сильные стороны и смыслы Вашего бизнеса или мероприятия. Составим Уникальное предложение (оффер)!
        </div>
        <div class="footer-image">
          <img src="./assets/1-6.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Suggestions'
  }
</script>

<style lang="scss" scoped>
  .suggestions {
    margin-bottom: 10.5vw;
    .header {
      display: flex;
      justify-content: center;
      color: #48578a;
      font-weight: bold;
      margin-bottom: 7.9vw;
    }
    .suggestion {
      margin: 0 0 30px;
      overflow: hidden;
      position: relative;
      padding: 40px 0 22px;
      height: 380px;
      background: white;
      border-radius: 7px;
      box-shadow: 0 0 15px lightgrey;
      .header {
        color: #2a313a;
        font-weight: bold;
        margin-bottom: 40px;
      }
      .main-text {
        padding: 0 30px 0;
        text-align: center;
        color: #676e78;
        max-height: 110px;
      }
      .footer-image {
        position: absolute;
        bottom: 22px;
        right: -10px;
        img {
          height: 80px;
        }
      }
    }
  }
</style>
