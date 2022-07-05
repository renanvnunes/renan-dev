<template>
	
	<div class="header-int">

		<div class="flex">
			
			<div class="text-center">
				<nuxt-img src="/img/me.jpg" class="shadow-lg" />
			</div>

			<div class="title"><b :class="`${color_title}`">{{ titulo }}</b></div>
					
			<!-- <div class="typer-style">
				<vue-typer
					:text='["Backend Developer", "Frontend Developer", "Ethical Hacking", "Servidores Linux"]'
					:repeat='Infinity'
					:shuffle='false'
					initial-action='typing'
					:pre-type-delay='70'
					:type-delay='70'
					:pre-erase-delay='2000'
					:erase-delay='250'
					erase-style='clear'
					:erase-on-complete='false'
					caret-animation='phase'
					></vue-typer>
			</div> -->
		</div>

	</div>

</template>

<script>

export default {
    name: "Header",
    transition: "slide-bottom",
	props: ['titulo', 'color_title']
}
</script>
