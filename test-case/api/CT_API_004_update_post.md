ID: CT_API_004
Título: Validar atualização de post existente

Tipo de Teste: Funcional API

Pré-condição:
Post existente na API

Passos:
1. Enviar requisição PUT para /posts/1
2. Enviar body JSON com dados atualizados
3. Verificar resposta da API

Resultado esperado:
Status code 200
Dados do post atualizados corretamente

Resultado obtido:
Status code 200
Post atualizado com sucesso
Body retornado:
{
 "id": 1,
 "title": "Post atualizado",
 "body": "Conteúdo atualizado",
 "userId": 1
}
