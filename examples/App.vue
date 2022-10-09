<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!--    <Demo/>-->
    <!--    <m-card-->
    <!--      img-src="/java.png"-->
    <!--      summary="剑指Java面试—Offer直通车  百度资深面试官授课"-->
    <!--    />-->
    <!--    <m-card-->
    <!--      img-src="/c.png"-->
    <!--      summary="C语言系统化精讲  重塑你的编程思维 打造坚实的开发基础"-->
    <!--    >-->
    <!--      <template v-slot:footer>-->
    <!--        <div class="footer">-->
    <!--          <div class="level">中级 · 1337人报名</div>-->
    <!--          <div class="price">¥299.00</div>-->
    <!--        </div>-->
    <!--      </template>-->
    <!--    </m-card>-->
    <!--    <br>-->
    <m-card
            img-src="/spring.png"
            :width="370"
            :img-height="90"
    >
      本路线旨在帮助想快速掌握SpringBoot应用的工程师，全方位多角度带你升级
      <template v-slot:footer>
        <div class="footer-spring">
          <div class="level">4步骤 · 6门课</div>
          <div class="level"></div>
        </div>
      </template>
    </m-card>
    <m-button text="普通按钮"></m-button>
  </div>
</template>

<script>

  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
