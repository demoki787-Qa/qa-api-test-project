ID: CT_API_003
Título: Validar criação de novo post

Tipo de Teste: Funcional API

Pré-condição:
API disponível para criação de registros

Passos:
1. Enviar requisição POST para /posts
2. Enviar body JSON com title, body e userId
3. Verificar resposta da API

Resultado esperado:
Status code 201
Novo registro criado
Retorno contendo ID do novo post

Resultado obtido:
Status code 201
Novo post criado com ID 101
Body retornado:
{
 "id": 101,
 "title": "Teste QA",
 "body": "Testando API",
 "userId": 1
}
