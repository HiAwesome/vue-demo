<!-- 模板部分 -->
<template>
  <p>{{ greeting }} World!</p>
</template>

<!-- 脚本部分 -->
<script>
export default {
  name: "v01_hello",
  data: function () {
    return {
      greeting: 'Hello'
    }
  }
}
</script>

<!-- 样式部分 -->
<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>