<template>
	<div>

		<Projeto />
		<HeaderInt titulo="PERFIL" color_title="perf-color" />

		<div class="pages">
			<div class="content shadow-sm bio">
				Renan Nunes, 31 anos, casado com Danielle, pai do Samuel de 8 anos..
				<br />
				Atuando em diversos projetos desde 2007. Em sua maioria, com foco em Backend.
				<br />
				<br />
				Busco sempre evoluir, aprender novas técnicas e novas linguagens, focando sempre em agilidade e performance no desenvolvimento. 
				<br />
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
