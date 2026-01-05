# Dicionário de Termos — API REST & Postman

## API
Interface que permite a comunicação entre sistemas por meio de requisições.

## Requisição (Request)
Chamada feita à API combinando método HTTP, endpoint e parâmetros para executar uma ação.

## Resposta (Response)
Retorno da API após a requisição, contendo dados e status.

## Endpoint
Combinação de método HTTP e caminho que identifica uma função específica da API.

## Path
Parte da URL que representa o recurso da API.
Ex: '/users/123'

## Método HTTP
Define a ação da requisição (GET, POST, PUT, PATCH, DELETE).

## Headers
Informações adicionais enviadas na requisição ou resposta.

## Body
Dados enviados na requisição, geralmente em formato JSON.

## Query Params
Parâmetros enviados na URL para filtros ou paginação.

## Status Code
Código numérico que indica o resultado da requisição (ex: 200, 400, 404, 500).

---

## Termos do Postman

## Collection
Conjunto de pastas e requisições usadas para organizar os testes de API.

## Folder
Agrupamento de requisições dentro de uma collection.

## Environment
Conjunto de variáveis que define o ambiente de execução (QA, Homologação, Produção).

## Variable
Valor reutilizável utilizado nas requisições (`{{base_url}}`, `{{token}}`).

## Pre-request Script
Script executado antes da requisição.

## Tests
Scripts executados após a resposta para validações.

## Runner
Ferramenta do Postman para executar collections em lote.

## Mock Server
Servidor simulado que retorna respostas pré-configuradas.

## Authorization
Configuração de autenticação usada nas requisições.

## Console
Área de logs do Postman para depuração.
