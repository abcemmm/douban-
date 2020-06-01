<template>
  <div id="content">
		<file-list></file-list>
		<pages></pages>
	</div>
</template>

<script>
import FileList from '@/components/FileList'
import Pages from '@/components/pages'
export default {
  data () {
    return {
      
    }
  },
	components:{
		FileList,
		Pages
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	#content{
		width: 1200px;
		margin: auto;
		background-color: #00FFFF;
	}
</style>
