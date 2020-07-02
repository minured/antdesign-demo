<template>
  <div id="app">
    hello
    <h2>按需引入, 通过 babel-plugin-import 自动转换import的路径</h2>
    <Button>ant design</Button>
  </div>
</template>

<script>
  //通过babel-plugin-import 转换为 import {Button} from "ant-design-vue/lib/button"
  import {Button} from 'ant-design-vue'

  export default {
    name: 'App',
    components: {
      Button
    }

  }
</script>

<style>

</style>
