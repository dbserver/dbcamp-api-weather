<p align="center">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/dbserver/dbcamp-weather-mock-api">
  <a href="https://github.com/dbserver/bcamp-weather-mock-api/commits/main">
  <img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/dbserver/dbcamp-weather-mock-api/main">
  </a>
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a href="https://db.tec.br/">
    <img alt="Feito pela DB" src="https://img.shields.io/badge/feito%20por-DB-%237519C1">
  </a>
</p>

# Weather Mock Api
## 💻 Sobre o projeto

🌤 **Weather Mock Api** - API JSON webserver que contém dados mockados metereológicos obtidos na api https://openweathermap.org.
Apresenta a informação metereológica atual e dos próximos 07 dias, das cidades:
- Porto Alegre / RS
- Charqueadas / RS
- São Luiz do Maranhão / MA
- Rio Grande /  RS
- Madre de Deus / BA

## Pré-requisitos

Você vai precisar ter instalado em sua máquina as seguintes ferramentas: [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
 Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🔂  Rodando o Back End (API)

### Clone o repositório
````
 $ git clone https://github.com/dbserver/dbcamp-weather-mock-api.git
````
### Rodando a api
````
json-server openweathermap.json
````
### Entrypoint API
````
http://localhost:3000
````
### GET all cities
Retorna uma lista de Cidades e suas previsões metereológicas.
````
http://localhost:3000/cities
````
### GET all citie by name
Retorna uma cidade e suas previsões metereológicas.
````
http://localhost:3000/cities?name=Porto Alegre
````