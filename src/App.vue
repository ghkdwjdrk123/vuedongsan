<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div>
    <h4>{{ products[0] }}</h4>
    <p>월 {{ prices[0] }} 만원</p>
  </div>
  <div>
    <h4>{{ products[1] }}</h4>
    <p>월 {{ prices[1] }} 만원</p>
  </div>
  <div>
    <h4>{{ products[2] }}</h4>
    <p>월 {{ prices[2] }} 만원</p>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      products: ['역삼동 원롬', '천호동 원룸', '마포구 원룸'],
      prices: ['50', '60', '70'],
    }
  },
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
