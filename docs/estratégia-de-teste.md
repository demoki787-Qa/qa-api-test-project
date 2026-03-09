# Estratégia de Testes - API JSONPlaceholder

## Objetivo
Definir a abordagem de testes utilizada para validar os endpoints da API JSONPlaceholder.

## Escopo
Testar os endpoints relacionados a gerenciamento de posts da API.

Endpoints testados:
- GET /posts
- GET /posts/{id}
- POST /posts
- PUT /posts/{id}

## Tipos de Teste

Testes Funcionais
Validação do funcionamento correto dos endpoints.

Testes de API
Verificação de requisições HTTP e respostas da API.

Testes de Validação de Dados
Verificação da estrutura do JSON retornado pela API.

Testes de Status Code
Validação dos códigos de resposta HTTP.

## Abordagem de Teste
Os testes foram realizados manualmente utilizando ferramenta de requisição HTTP (Hoppscotch).

Cada endpoint foi validado através de:
- envio de requisição
- verificação do status code
- análise da estrutura da resposta JSON

## Ferramentas Utilizadas

Hoppscotch  
GitHub  
SQL  

## Evidências

As evidências dos testes estão disponíveis na pasta:

/evidence/api
