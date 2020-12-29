<!-- 模板部分 -->
<template lang="jade">
div
  p {{
    greeting
  }} World!
   other-component

</template>

<!-- 脚本部分 -->
<script>
/* 引入其他组件 */
import OtherComponent from './v02_other_component'

export default {
  name: "v01_hello",
  data: function () {
    return {
      greeting: 'Hello'
    }
  },
  components: {
    OtherComponent
  }
}
</script>

<!-- 样式部分 -->
<style lang="stylus" scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>