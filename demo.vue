<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>搭建配置一个线上生产环境，把应用部署到服务器中，通过域名再暴露到互联网上，主要有这几件事情大家需要了解下：     </p>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Vue 前端项目部署案例'
    }
  }
}
</script>

<style scoped>
  .hello {
    width: 680px;
    margin: 0 auto;
    text-align: left;
  }
  h1 {
    text-align: center;
  }
</style>