---
title: "Portfolio Remake"
layout: projeto
description: Object Oriented Design<br>Working with Jekyll
image: assets/images/portfolio/portfolio_capa.jpg
nav-menu: true
show_tile: true
permalink: /portfolio/
---
<!-- Instruções>
<!-- Neste arquivo mudar somente o frontmater e os partes a seguir:>
<!-- Alterar o loop for com o nome do arquivo e seção do arquivo nas tres partes>
<!-- Colocar a descrição.yml dentro da pasta _data e mudar pelo (projeto_de_teste)>
<!-- Dentro do arquivo do projeto_de_teste, especificar cada uma das seções>
<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
{% for item in site.data.portfolio.intro %}
	<div class="inner">
		<header class="major">
			<h2>{{item.title}}</h2>
		</header>
		<p>{{item.content}}</p>
	</div>
	{% endfor %}
</section>

<!-- Two -->
<section id="two" class="spotlights">
{% for item in site.data.portfolio.conteudo %}
   <section>
  <img src="{{item.image}}" alt="" data-position="center center" class="image"/>
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
{% for item in site.data.portfolio.conclusao %}
	<div class="inner">
		<header class="major">
			<h2>{{item.title}}</h2>
		</header>
		    <p>{{item.content}}</p>
		<ul class="actions">
			<li><a href="/home/" class="button next">back to home</a></li>
		</ul>
	</div>
{% endfor %}
</section>

</div>
