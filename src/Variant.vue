<template>
  <div class="variant">
    <div class="main">
      <div class="image">
        <slot name="image"></slot>
      </div>
      <div class="header">
        <span class="font-weight-bold"><slot name="header"></slot></span>
      </div>
      <div class="description">
        <span><slot name="description"></slot></span>
      </div>
    </div>
    <div class="actions">
      <div class="button">
        <span>ВЫБРАТЬ ПЛАН</span>
      </div>
      <a href="" class="description-link">
        <span>Подробнее</span>
      </a>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'variant'
  }
</script>

<style lang="scss" scoped>
  .variant {
    text-align: center;
    height: 470px;
    padding: 30px 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    .main {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      .image {
        margin-bottom: 20px;
        img {
          height: 100px;
        }
      }
      .header {
        color: #2a313a;
        font-weight: bold;
        margin-bottom: 20px;
        font-size: 16px;

      }
      .description {
        color: #676e78;
        font-size: 13px;
      }
    }
    .button {
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      width: 100%;
      border-radius: 21px;
      border: solid #48578a 2px;
      height: 40px;
      color: #48578a;
      margin-bottom: 15px;
      &:hover {
        box-shadow: 0 0 15px #48578a;
        background: #48578a;
        cursor: pointer;
        color: white;
      }
    }
    .description-link {
      visibility: hidden;
      text-decoration: none;
      font-size: small;
      color: #48578a;
      font-weight: bold;
    }
    &:hover {
      background: white;
      border-radius: 7px;
      box-shadow: 0 0 15px lightgrey;
      .description-link {
        visibility: visible;
      }
    }
  }
</style>
