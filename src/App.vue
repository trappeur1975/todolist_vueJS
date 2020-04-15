<template>
	<div>
		<todolist></todolist>
		<todolist></todolist>
		<todolist></todolist>
	</div>
</template>

<script>
	import Todolist from './components/Todolist'

	export default {
	  // name: 'App',
	  components: {
	    Todolist
	  }
	}
</script>