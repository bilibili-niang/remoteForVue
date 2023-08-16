<template>
  <div class="hello">
    你好,这是我的测试发布的包
    <br>
    不知道能不能访问到,
    <br>
    <pre>
      <code>
        // 13
          /**
          * @param {string} s
          * @return {number}
          */
      </code>
    </pre>
  </div>
</template>

<script>

export default {
  name: "HelloWorld",
  components: {
  },
  props: {
    msg: String,
  },
};
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
