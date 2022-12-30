---
title: Tteste
layout: projeto
description: rápida descrição
image: assets/images/pic07.jpg
nav-menu: true
show_tile: true
permalink: /projeto_teste/
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
	<!-- {% include proj_teste/p_t_p01.html %} desativado -->
     {% for item in site.data.projeto_de_teste.conteudo %}
  <section>
  <img src="{{item.image}}" alt="" data-position="center center" />
    <div class="content">
      <div class="inner">
        <header class="major">
          <h3>{{item.title}}</h3>
        </header>
        <p>{{item.content}}</p>
      </div>
    </div>
    </section>
    {% endfor %}
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
