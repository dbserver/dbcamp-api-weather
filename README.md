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

### GET  City by name 
````
http://localhost:3000/cities?name=Porto Alegre
