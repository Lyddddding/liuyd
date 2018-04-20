<template>
  <div id="app">
    <router-view></router-view>  <!--显示当前路由对应的组件-->
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style  scoped>
	
</style>


<!--
	单文件组件 指的是组件的样式，模版，逻辑都写在一个组件里
{
	template
	data
}
-->