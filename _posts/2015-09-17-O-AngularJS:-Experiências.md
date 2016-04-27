---
layout: impress
title:  "O AngularJS - Experiências"
description: Single Page Application, Injection Dependency, RESTful, User Experience, MVC and more...
tags: Injection Dependency, RESTful, User Experience, MVC, jax-rs, maven, jpa, archtecture, Single Page Application
categories: angularjs, framework, 
---


<div class="step slide" data-x="-2000" data-y="-1000" 	>
	<q>O <b>AngularJS</b>, assim como outros frameworks dotJS, vem ganhando bastante notoriedade nos últimos anos.</q>
</div>

<div  class="step slide" data-x="-2000" data-y="0">	
<q>Mas, porque usar o AngularJS ?</q>
</div>

<div  class="step slide" data-x="-2000" data-y="1000" >	
<q>
<ul>
	<li>O Angular manipula o DOM transparentemente.</li>
	<li>Proporciona um alto reuso oferecendo um grande poder de modularização (diretivas).</li>
	<li>Além disso fornece funções nativas que facilitam as atualizações de valores (bind) e integrações a chamadas REST (resources). </li>
	<li>Facilita a criação de <b>Single Pages Application</b>.</li>
</ul>
</q>
</div>

<div  markdown="1" class="step slide" data-x="2000" data-y="-1000"  >	
<h1>Motivação</h1>
<q>Construção de [Single Pages Application](https://en.wikipedia.org/wiki/Single-page_application)
favorecem uma boa [User Experience (UX)](https://pt.wikipedia.org/wiki/Experi%C3%AAncia_do_usu%C3%A1rio). O AngularJS ajuda a trazer uma boa experiência de navegação para o cliente sem <b class="scaling">pop-ups</b> e <b class="scaling">submits</b> de forma <b class="positioning"> simples e nativa</b>
</q>
</div>

<div markdown="1" class="step slide" data-x="2000" data-y="0" >	
<q>Na epoca que me formei (nao faz tanto tempo assim e me lembro muito bem) o AJAX era um sonho, Web 2.0 era o diferencial no desenvolvimento de softwares de arquitetura 3 camadas. Hoje, isso esta tão inerente aos frameworks em JavaScript que nem preocupa mais. O que mudou foi a forma como uma aplicacao web poderia ser construida focando na escalabilidade, com baixo custo em manutencao, com codigo gerado em runtime, baixo nivel de acoplamento, com uma arquitetura bem definida e assim por diante...
</q>
</div>
<div markdown="1" class="step slide" data-x="2000" data-y="1000" >	
<q>O fato de se utilizar [Single Pages Application](https://en.wikipedia.org/wiki/Single-page_application) , me fez ainda pensar sobre um problema muito pouco comum nas aplicacoes WEB que seria: Então minhas regras de negocio estariam na web (no javascript) uma vez que o codigo poderia ser acessado e baixado? Para que serveria então o controller do AngularJS? Como ficaria então essa questão? 
Estudando um pouco mais a fundo e entendendo os Controllers, Filters, Directives, Constants e etc.. do framework,
decidi manter as regras de negocio no backend, assim como os models e a camada de seguranca e comecei a utilizar usar [SPA](https://en.wikipedia.org/wiki/Single-page_application) com uma API. Isso me possibilitaria rodar no backend o NODEJS, ou o JAVAEE, ou o PHP, ou qualquer outra linguagem que se comunicasse com o FORNTEEND usando [RESTFUL](https://en.wikipedia.org/wiki/Representational_state_transfer) .
</q>
</div>
<div markdown="1" class="step slide" data-x="6000" data-y="0" >	
<q>Dessa forma podia utilzar o AngularJS para compreender comportamentos do usuario, para exibir, converter e adaptar os dados do negocio (por exemplo de HTML para PDF), trazer uma maior experiencia com respostas mais rapidas, tudo isso de forma dinamica, transparente e segura.
</q>
</div>
<div markdown="1" class="step slide" data-x="7000" data-y="0" >	
<q>Logo depois de estudar bastante esse framework, decidi criar uma arquitetura simples em 3 camadas com um backend leve e um frontend que pudesse ser poderoso o bastante para atender aos novos requistos de forma modular.
</q>
</div>

<div markdown="1" class="step slide" data-x="8000" data-y="0">	
<q>Visao Estrutural da Arquitetura Completa:
![Arquitetura ](/assets/images/AngularJS_SPA.png)
</q>
</div>

<div markdown="1" class="step slide" data-x="9000" data-y="0">	
<q>FRONTEND:

Static Component:
    ![StaticComponent](/assets/images/AngularJS_SPA_StaticComponent.png)
 </q>
 </div>

<div markdown="1" class="step slide" data-x="10000" data-y="0">	
<q>FRONTEND:

Angular Component :
    ![Angular_App](/assets/images/AngularJS_SPA_AngularApp.png)
 </q>
 </div>
<div markdown="1" class="step slide" data-x="11000" data-y="0">	
<q>BACKEND:

API Component :
    ![AngularJS_SPA_backend](/assets/images/AngularJS_SPA_backend.png)
 </q>
 </div>
<div markdown="1" class="step slide" data-x="12000" data-y="0">	
<q>Ainda estou trabalhando nessa arquitetura pois ainda existe muito acoplamento onde nao deveria existir e cada vez mais que uso o AngularJS entendo muito o porque desse framework esta entre os mais usados do mundo.
 </q>
 </div>



