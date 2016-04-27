---
layout: impress
title:  "O AngularJS - Experiências"
description: Single Page Application, Injection Dependency, RESTful, User Experience, MVC and more...
tags: Injection Dependency, RESTful, User Experience, MVC, jax-rs, maven, jpa, archtecture, Single Page Application
categories: angularjs, framework, 
---

 {::options parse_block_html="true" /}

<div class="step slide" data-x="0" data-y="-3500" >
Desde o ano de 2014 venho estudando sobre o AngularJS. 
Nesse periodo tenho notado que o AngularJS e outros frameworks *JS vem ganhando bastante notoriedade.

</div>

<div  class="step slide" data-x="1000" data-y="-3500" >	
Mas, porque usar o AngularJS ? Seria porque e um projeto que o google mantem? Ou seria mais uma "modinha"?
Ou seria pelo fato de possibilitar uma grande escalabilidade? 
Proporcionar um alto reuso? 
ou ainda poder modularizar aplicaçoes [Single Pages Application](https://en.wikipedia.org/wiki/Single-page_application) em tempo real? (explicarei isso mais tarde, prometo).
</div>
<div class="step slide" data-x="2000" data-y="-3500"  >	
Bom, para começar, minha motivaçao inical em usar AngularJS foi a construçao de [Single Pages Application](https://en.wikipedia.org/wiki/Single-page_application) .
Isso me fez pensar muito sobre [User Experience (UX)](https://pt.wikipedia.org/wiki/Experi%C3%AAncia_do_usu%C3%A1rio) pois meu maior objetivo como programador (até hoje), tem sido trazer uma boa experiencia de navegacao para o cliente.
</div>
<div class="step slide" data-x="0" data-y="-2500" >	
Na epoca que me formei (nao faz tanto tempo assim e me lembro muito bem) o AJAX era um sonho, Web 2.0 era o diferencial no desenvolvimento de softwares de arquitetura 3 camadas. Hoje, isso esta tão inerente aos frameworks em JavaScript que nem preocupa mais. O que mudou foi a forma como uma aplicacao web poderia ser construida focando na escalabilidade, com baixo custo em manutencao, com codigo gerado em runtime, baixo nivel de acoplamento, com uma arquitetura bem definida e assim por diante...
</div>
<div class="step slide" data-x="1000" data-y="-2500" >	
O fato de se utilizar [Single Pages Application](https://en.wikipedia.org/wiki/Single-page_application) , me fez ainda pensar sobre um problema muito pouco comum nas aplicacoes WEB que seria: Então minhas regras de negocio estariam na web (no javascript) uma vez que o codigo poderia ser acessado e baixado? Para que serveria então o controller do AngularJS? Como ficaria então essa questão? 
Estudando um pouco mais a fundo e entendendo os Controllers, Filters, Directives, Constants e etc.. do framework,
decidi manter as regras de negocio no backend, assim como os models e a camada de seguranca e comecei a utilizar usar [SPA](https://en.wikipedia.org/wiki/Single-page_application) com uma API. Isso me possibilitaria rodar no backend o NODEJS, ou o JAVAEE, ou o PHP, ou qualquer outra linguagem que se comunicasse com o FORNTEEND usando [RESTFUL](https://en.wikipedia.org/wiki/Representational_state_transfer) .
</div>
<div class="step slide" data-x="2000" data-y="-2500" >	
Dessa forma podia utilzar o AngularJS para compreender comportamentos do usuario, para exibir, converter e adaptar os dados do negocio (por exemplo de HTML para PDF), trazer uma maior experiencia com respostas mais rapidas, tudo isso de forma dinamica, transparente e segura.
</div>
<div class="step slide" data-x="0" data-y="-1500" >	
Logo depois de estudar bastante esse framework, decidi criar uma arquitetura simples em 3 camadas com um backend leve e um frontend que pudesse ser poderoso o bastante para atender aos novos requistos de forma modular.
</div>

<div class="step slide" data-x="1000" data-y="-1500">	
Visao Estrutural da Arquitetura Completa:
![Arquitetura ](/assets/images/AngularJS_SPA.png)
</div>

<div class="step slide" data-x="2000" data-y="-1500">	
FRONTEND:

Static Component:
    ![StaticComponent](/assets/images/AngularJS_SPA_StaticComponent.png)
 </div>

<div class="step slide" data-x="0" data-y="-500">	
FRONTEND:

Angular Component :
    ![Angular_App](/assets/images/AngularJS_SPA_AngularApp.png)
 </div>
<div class="step slide" data-x="1000" data-y="-500">	
BACKEND:

API Component :
    ![AngularJS_SPA_backend](/assets/images/AngularJS_SPA_backend.png)
 </div>
<div class="step slide" data-x="2000" data-y="-500">	
Ainda estou trabalhando nessa arquitetura pois ainda existe muito acoplamento onde nao deveria existir e cada vez mais que uso o AngularJS entendo muito o porque desse framework esta entre os mais usados do mundo.
 </div>

<div id="overview" class="step" data-x="1000" data-y="-2000" data-scale="4">

</div>


