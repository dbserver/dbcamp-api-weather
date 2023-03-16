# Weather API

API JSON webserver que contém dados metereológicos obtidos em https://openweathermap.org.


## Executando o Projeto 💻
### Instalando os módulos

````
npm install
````

### Rodando a API

````
json-server openweathermap.json
````

## Endpoints da API

### Entrypoint API
````
http://localhost:3000
````

### GET all cities
Retorna uma lista de Cidades e suas previsões metereológicas
````
http://localhost:3000/cities
````

## Regras de Negócio

Após a busca das informações de uma cidade, devo mostrar no app:

### DOC com informações dos campos retornados na API:
https://openweathermap.org/api/one-call-3#parameter

### **Histórias de Usuário:**

**-> Pesquisar dados metereologicos de uma cidade para visualizar informações atuais**
-  *Objetivo:*
	**Como** – usuário
	**quero**– pesquisar por uma cidade
	**para** – visualizar informações metereológicas do dia atual 
	
**-> Pesquisar dados metereologicos de uma cidade para visualizar previsão para os próximos 07 dias**
-  *Objetivo:*
	**Como** – usuário
	**quero**– pesquisar por uma cidade
	**para** – visualizar previsão metereológica para os próximos 07 dias 


