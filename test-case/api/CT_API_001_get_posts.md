ID: CT_API_001
Título: Validar retorno da lista de posts

Tipo de Teste: Funcional API

Pré-condição:
API JSONPlaceholder disponível

Passos:
1. Enviar requisição GET para /posts
2. Verificar status code da resposta
3. Verificar estrutura do JSON retornado

Resultado esperado:
Status code 200
Lista de posts retornada
Campos presentes:
userId
id
title
body
