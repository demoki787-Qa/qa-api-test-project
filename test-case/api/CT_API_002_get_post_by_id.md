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
Retorno de objeto JSON contendo:
userId
id
title
body
