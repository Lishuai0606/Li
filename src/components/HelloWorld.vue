<template>
  <div class="hello">
    <p>从新开始</p>
    <p>李帅</p>
    <p>李帅1</p>
    <p>张豪</p>
    <p>
      李帅2
    </p>
    <p>张豪2</p>
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
