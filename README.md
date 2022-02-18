<h1 align="center">API JCPIMOVEIS </h1>

Esta API foi feita para auxiliar na apresentação da plataforma de cadastro de vendas e alugueis de imóveis..

<h4 style="font-weight:bold; color:green">=> Endereço base
(base_url) </h4>

https://backend-jcpimoveis.herokuapp.com

<h4 style="font-weight:bold; color:green">EndPoints:</h4>

Proprietários: /owners <br />
Imóveis: /properties 

<h4 style="font-weight:bold; color:green">=> Rotas</h4>

As rotas definem como você vai acessar a API.<br />
As rotas são:

<h4 style="font-weight:bold; color:purple">Proprietários</h4>

GET /owners <=> Busca todos os proprietários<br />
GET /owners/1 <=> Busca um proprietário<br />
POST /owners <=> Adiciona um proprietário<br />
PUT /owners/1 <=> Atualiza dos os dados do proprietário<br />
DELETE /owners/1 <=> Remove um proprietário

<h4 style="font-weight:bold; color:greenyellow">Imóveis</h4>

GET /properties <=> Busca todos os imóveis<br />
GET /properties/1 <=> Busca um imóvel<br />
POST /properties <=> Adiciona um imóvel<br />
PUT /properties/1 <=> Atualiza dos os dados do imóvel<br />
DELETE /properties/1 <=> Remove um imóvel

====================================================