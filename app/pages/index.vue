<script len="ts" setup>
const { data: tasks, error, status } = await useFetch("/api/tasks");
</script>

<template>
	<article
		v-for="task in tasks"
		:key="task.id"
	>
		{{ task.title }}
	</article>
</template>
