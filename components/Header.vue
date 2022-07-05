<template>
	
	<div class="header">

		<div class="grid-content text-center">
			<nuxt-img src="/img/me.jpg" class="shadow-lg" />
			<div class="title">RENAN <b>NUNES</b></div>
		</div>
	
		<div class="typer-style">
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
		</div>

		<div class="address">
			<div>Maringá-PR / Indianópolis-PR - renan.dev@hotmail.com</div>
			<div> <i class="el-icon-mobile-phone"></i> <b>44 9 9156-9900</b></div>
		</div>

		<div class="menu">
			<ul>
				<li><nuxt-link to="/perfil">PERFIL</nuxt-link></li>
				<li><nuxt-link to="/tecnologias">TECNOLOGIAS</nuxt-link></li>
				<li><nuxt-link to="/experiencias">EXPERIÊNCIAS</nuxt-link></li>
			</ul>
		</div>

	</div>

</template>

<script>

export default {
    name: "Header",
    transition: "slide-bottom",
}
</script>
