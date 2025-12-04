<template>
	<nav class="container">
		<ul>
			<li>
				<nuxt-link to="/">
					<strong>Tasks App</strong>
				</nuxt-link>
			</li>
		</ul>
		<ul>
			<li><NuxtLink :to="{ name: 'create' }">create</NuxtLink></li>
		</ul>
	</nav>
</template>
