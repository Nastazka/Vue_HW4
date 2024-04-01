<template>
  <div id="app">
    <div class="container">
      <header-component></header-component>
      <div class="blog">
        <p class="blog-title">Articles & News</p>
        <p class="blog-subtitle">It is a long established fact that a reader will be distracted by the of readable content of a page when lookings at its layouts the points of using.</p>
        <articles-component></articles-component>
      </div>
      <footer-component></footer-component>
    </div>
  </div>
</template>

<script>
import ArticlesComponent from './components/ArticlesList.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    ArticlesComponent,
    HeaderComponent,
    FooterComponent
  }
}
</script>

<style>
.container {
    width: 1200px;
    margin:  0 360px 0 360px;
}
.blog-title {
    font-family: DM Serif Display;
    font-size: 50px;
    font-weight: 400;
    line-height: 63px;
    letter-spacing: 0.02em;
    text-align: center;
}
.blog-subtitle {
    font-family: Jost;
    font-size: 22px;
    font-weight: 400;
    line-height: 33px;
    letter-spacing: 0.01em;
    text-align: center;
    width: 811px;
    margin-left: 195px;
}
</style>