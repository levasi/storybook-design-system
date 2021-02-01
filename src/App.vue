<!-- src/App.vue -->

<template>
	<div id="app">
		<InboxScreen />
	</div>
</template>

<script>
import InboxScreen from './components/InboxScreen.vue';
export default {
	name: 'app',
	components: {
		InboxScreen,
	},
};
</script>

<style>
</style>