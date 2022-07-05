<template>
	<div>

		<Projeto />
		<HeaderInt titulo="EXPERIÊNCIAS" />

		<div class="pages">
			<div class="content shadow-sm bio">
				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facilis ad dolore voluptas, animi maiores quae minima, ab, quidem non sapiente exercitationem culpa impedit doloribus alias laboriosam a in illo veniam!
			</div>
			
			<nuxt-link class="back" to="/">Voltar</nuxt-link>
		</div>

	</div>
</template>

<script>
export default {
    name: "Header",
    transition: "slide-bottom",
}
</script>
