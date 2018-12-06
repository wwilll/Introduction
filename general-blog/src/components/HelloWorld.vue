<template>
  <div class="hello">
    <h1>parent's params:{{ msg }}</h1>
    <p>I'm HelloWorld Component</p>
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
<style scoped lang="less">
.hello {
  border: 1px solid red;
  background-color: rgb(206, 194, 194);
  h1 {
    background-color: skyblue;
  }
}

</style>
