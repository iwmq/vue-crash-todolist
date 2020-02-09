<template>
  <div class="hello">
    <h1>Hello World</h1>
    <p>Vue.js is very very handy and easy to learn!</p>
    <p><small>{{ msg }}</small></p>
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
h1 {
  margin: 20px 0 0;
  color: #42b983;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
p {
  color: #ff3333;
  font-size: 1.4em;
}
a {
  color: #42b983;
}
</style>
