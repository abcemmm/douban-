<template>
  <div id="app">
		<home-title></home-title>
		<home-content></home-content>
  </div>
</template>

<script>
import HomeTitle from '@/components/HomeTitle'
import HomeContent from '@/components/HomeContent'
export default {
  name: 'App',
	components:{
		HomeTitle,
		HomeContent
	}
}
</script>

<style>
#app {
  
	*{
		margin: 0;
		padding: 0;
	}
}
</style>
