ID: CT_API_002
Título: Validar retorno de post por ID

Tipo de Teste: Funcional API

Pré-condição:
API JSONPlaceholder disponível

Passos:
1. Enviar requisição GET para /posts/1
2. Verificar status code da resposta
3. Validar dados retornados

Resultado esperado:
Status code 200
Objeto JSON retornado contendo: userId, id, title, body

Resultado obtido:
Status code 200
Objeto JSON retornado corretamente:
{
 "userId": 1,
 "id": 1,
 "title": "sunt aut facere",
 "body": "quia et suscipit"
} 
