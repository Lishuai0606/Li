<template>
  <div class="hello">
    <p>
      你是谁
      <samp>我是谁
        <samp>你有是说</samp>
      </samp>
    </p>
    <p>master上的代码</p>
    <p>dev上的代码</p>
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
h3 {
  margin: 40px 0 0;
}
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
