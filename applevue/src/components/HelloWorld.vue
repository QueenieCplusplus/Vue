<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://github.com/QueenieCplusplus" target="_blank" rel="noopener">PKQ's Github</a>.
    </p>

    <ul>
      <li><a href="https://www.ebaomonthly.com/window/photo/lesson/colorList.htm" target="_blank" rel="noopener">Color Art Gallery</a></li>
    </ul>
    
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
  margin: 10px 0 0;
}
ul {
  list-style-type: none;
  padding: 30;
}
li {
  display: inline-block;
  margin: 20 30px;
}
a {
  color: #F08080;
}
</style>
