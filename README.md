# Tech Challenge FIAP - Grupo 12 - Fase 1

## 🚀 Sobre o projeto 

### Escopo:

Analisar os dados de vitivinicultura da Embrapa, os quais estão disponíveis em http://vitibrasil.cnpuv.embrapa.br/index.php.

A ideia do projeto é a criação de uma API pública de consulta nos dados do site nas respectivas abas:

* Produção
* Processamento
* Comercialização
* Importação
* Exportação

A API vai servir para alimentar uma base de dados que futuramente será usada para alimentar um modelo de Machine Learning.

### Objetivos da fase 1:

- Criar uma Rest API em Python que faça a consulta no site da Embrapa.
- A API deve estar documentada.
- É recomendável (não obrigatório) a escolha de um método de autenticação (JWT, por exemplo).
- Criar um plano para fazer o deploy da API, desenhando a arquitetura do projeto desde a ingestão até a alimentação do modelo (aqui não é necessário elaborar um modelo de ML, mas é preciso que vocês escolham um cenário interessante em que a API possa ser utilizada).
- Fazer um MVP realizando o deploy com um link compartilhável e um repositório no github.

## 📋 Pré-requisitos

- Interpretador Python para execução dos códigos;
- Biblioteca FastAPI para criação da API;
- Biblioteca Uvicorn para criação de servidor da API.
- Biblioteca Streamlit para criação de interface de requisições da API.

## 🔧 Instalação
Para criação do ambiente virtual, abra o diretório do projeto e execute os seguintes comandos no terminal:
````
python -m venv nomeDoAmbienteVirtual

.\nomeDoAmbienteVirtual\Scripts\activate
````
Para instalação das dependências, execute o seguinte comando:
````
pip install -r requirements.txt
````

## ⚙️ Execução
Para execução do servidor Uvicorn da API, e da interface Streamlit, abra dois terminais no diretório base do projeto e execute os seguintes comandos:
- Terminal 1:
````
.\nomeDoAmbienteVirtual\Scripts\activate

uvicorn main:api
````
- Terminal 2:
````
.\nomeDoAmbienteVirtual\Scripts\activate

streamlit run app.py
````

Com os dois terminais rodando as respectivas aplicações, é possível fazer requisições à plataforma do Embrapa através de requests na interface do Streamlit.

## ✒️ Autores

Isabelli Andrade de Souza - https://github.com/Isabellitankian
<br>
Lucas Souza Andrade dos Santos - https://github.com/LSouzaAndrade
<br>
Michel de Lima Maia - https://github.com/Michel-Maia
<br>
Valquiria Rodrigues de Oliveira Pires - https://github.com/KyraPires
