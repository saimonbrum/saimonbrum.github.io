---
title: Template de Projeto
layout: projeto
description: rápida descrição
image: assets/images/pic07.jpg
nav-menu: true
show_tile: true
permalink: /template_projeto/
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Aqui vai o título de início</h2>
		</header>
		<p>aqui vai a descrição do projeto e a equipe envolvida</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<img src="{% link assets/images/pic08.jpg %}" alt="" data-position="center center" />
			<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Primeira parte</h3>
				</header>
				<p>Verificar como colocar esse title e esse content em um arquivo na pasta data, no projeto de mesmo nome, e usar variáveis para puxar pra cá.</p>
                <p>Aqui vai a conclusão do parágrafo.
                </p>
			</div>
		</div>
	</section>
	<section>
			<img src="{% link assets/images/pic09.jpg %}" alt="" data-position="top center" />
			<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Parte 2</h3>
				</header>
				<p>Aqui posso linkar para outra parte.md com include e novamente usar tags para filtrar posteriormente.</p>
            </div>
		</div>
	</section>
	<section>
		<img src="{% link assets/images/pic10.jpg %}" alt="" data-position="25% 25%" />
		    <div class="content">
			<div class="inner">
				<header class="major">
					<h3>Parte 3</h3>
				</header>
				<p>Mais um include que vai permitir filtrar quais etapas de design fiz em cada projeto.</p>
			</div>
		</div>
	</section>
    <section>
		<img src="{% link assets/images/pic10.jpg %}" alt="" data-position="25% 25%" />
		    <div class="content">
			<div class="inner">
				<header class="major">
					<h3>Parte 4</h3>
				</header>
				<p>Só para testar se as imagens alternadas são automáticas.</p>
                <p>R: Sim</p>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Conclusão</h2>
		</header>
		    <p>O que aprendi com esse projeto.</p>
            <p>O que faria diferente.</p>
            <p>Usar o botão para voltar pra home.</p>
		<ul class="actions">
			<li><a href="generic.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
