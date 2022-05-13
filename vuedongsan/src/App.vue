<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <div>
    <h4>{{ products[0] }}</h4>
    <p>50 만원</p>
  </div>
  <div>
    <h4>{{ products[1] }}</h4>
    <p>가격은 아무거나</p>
  </div>
  <div>
    <h4>{{ products[2] }}</h4>
    <p>가격은 아무거나</p>
  </div>
</template>

<script>
//document.getElementById().innerHTML = ??  기존의 자바스크립트 문법

export default {
  name: "App",
  data() {
    //데이터 보관 통, 데이터는 object형으로 저장
    return {
      price1: 60,
      price2: 70,
      products: ["역삼동원룸", "천호동원룸", "마포구원룸"],
    };
  },
  components: {},
};
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
