<template>
  <div class="variants">
    <div class="header">
      <h2 class="higher">
        Мы знаем, как и где искать Ваших клиентов и как их заинтересовать Вашим предложением.
      </h2>
      <h4 class="lower">
        Результат продвижения будет заметен в течение 1 месяца!
      </h4>
    </div>
    <div class="main">
      <h2 class="header">Варианты работы над вашим проектом</h2>
      <div class="variants-container row">
        <variant class="col-3">
          <template slot="image"><img src="./assets/3-1.png"></template>
          <template slot="header">Работаем над отдельными услугами</template>
          <template slot="description">Делаем Landing-Page, SMM, SEO, контекст, таргетинг, дизайн, упаковку. Оплата за конкретную услугу</template>
        </variant>
        <variant class="col-3">
          <template slot="image"><img src="./assets/3-2.png"></template>
          <template slot="header">Комплексное продвижение с атрибутами</template>
          <template slot="description">Оплата за комплекс услуг, с возможными бонусами</template>
        </variant>
        <variant class="col-3">
          <template slot="image"><img src="./assets/3-3.png"></template>
          <template slot="header">Услуга работы на конкретно заданные показатели</template>
          <template slot="description">Оплата за достижение показателей (число посещений, ЛИД-ов, конверсию и т.д.)</template>
        </variant>
        <variant class="col-3">
          <template slot="image"><img src="./assets/3-4.png"></template>
          <template slot="header">Разрабатываем специальное предложение</template>
          <template slot="description">Оплата устанавливается как % с каждой продажи ваших товаров или услуг</template>
        </variant>
      </div>
    </div>
  </div>
</template>

<script>
  import Variant from './Variant'

  export default {
    components: {Variant},
    name: 'Variants'
  }
</script>

<style lang="scss" scoped>
  .variants {
    .header {
      text-align: center;
      margin-bottom: 7.94vw;
      .higher {
        color: #242424;
        margin-bottom: 3.68vw;
      }
      .lower {
        color: #616161
      }
    }
    .main {
      width: 100%;
      background: white;
      border-radius: 7px;
      box-shadow: 0 0 15px lightgrey;
      padding: 70px 30px 47px;
      margin-bottom: 200px;
      .header {
        margin-bottom: 45px;
        color: #48578a;
      }
      .variants-container {
        height: 400px;
      }
    }
  }
</style>
