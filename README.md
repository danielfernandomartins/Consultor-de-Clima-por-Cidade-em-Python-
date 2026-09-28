# Consultor de Clima por Cidade em Python

Projeto desenvolvido em Python para consultar informações climáticas de uma cidade utilizando uma API pública.

O programa recebe o nome de uma cidade, consulta sua localização e depois busca informações sobre o clima atual.

## Funcionalidades

- Buscar uma cidade pelo nome
- Consultar latitude e longitude
- Exibir estado e país
- Consultar temperatura atual
- Exibir sensação térmica
- Exibir umidade do ar
- Exibir velocidade do vento
- Tratamento básico para cidade não encontrada

## Tecnologias utilizadas

- Python
- Biblioteca `requests`
- API Open-Meteo
- Google Colab

## Conceitos praticados

Neste projeto foram utilizados conceitos importantes de Python e consumo de APIs:

- Funções
- Variáveis
- Estruturas condicionais
- Dicionários
- Requisições HTTP
- Método GET
- Parâmetros de requisição
- Código de status HTTP
- JSON
- Manipulação de dados retornados por API
- `requests.get()`
- `response.status_code`
- `response.json()`
- `.get()`

## Como funciona

O fluxo do programa é:

```text
Usuário
   ↓
Digita o nome da cidade
   ↓
Python consulta a API
   ↓
API retorna dados em JSON
   ↓
Python trata os dados
   ↓
Informações do clima são exibidas
