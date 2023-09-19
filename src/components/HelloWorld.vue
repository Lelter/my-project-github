<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      姓名：叶宇涛
    </p>
    <h3>昵称</h3>
    <ul>
      <li>Lelter</li>
    </ul>
    <h3>爱好</h3>
    <ul>
      <li>游戏</li>
      <li>看番</li>
      <li>睡觉</li>
      <li>打球</li>
    </ul>
   <h1 style="color:#189a18">谢谢大家！</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
