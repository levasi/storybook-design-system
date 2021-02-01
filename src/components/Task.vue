<!-- src/components/Task.vue -->

<template>
	<div class="list-item">
		<input
			type="text"
			readonly
			:value="task.title"
		/>
	</div>
</template>

<script>
export default {
	name: 'Task',
	props: {
		task: {
			type: Object,
			required: false,
			default: () => ({ id: '', state: '', title: '' }),
			validator: task => ['id', 'state', 'title'].every(key => key in task),
		},
	},
};
</script>