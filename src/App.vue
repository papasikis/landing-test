<template>
  <div class="arrow">
    <Header></Header>
    <div class="main">
      <Suggestions></Suggestions>
      <Variants></Variants>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import Suggestions from './Suggestions'
import Variants from './Variants'
import Header from './Header'
import Footer from './Footer'

export default {
  name: 'app',
  components: {
    Header,
    Variants,
    Suggestions,
    Footer
  }
}
</script>

<style lang="scss">
  @import "sass/main.scss";
  html {
    height: 100%;
  }
  body {
    background-color: #f5f5f5;
  }
  .arrow {
    font-family: Lato;
    & > .main {
      padding: 0 19%;
      background-image: url("./assets/body-background.png");
      background-size: cover;
    }
  }
</style>
