<template>
  <div id="app">
  	<div @click="handleClick" class="dell">{{message}}</div>
    <!--<router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
  	return {
  		message: 'HelloWorld'
  	}
  },
  methods: {
  	handleClick () {
  		this.message = 'ByeByeWorld'
  	}
  }
}
</script>

<style  scoped>
	.dell {
		color: red;
	}
</style>


<!--
	单文件组件 指的是组件的样式，模版，逻辑都写在一个组件里
{
	template
	data
}
-->