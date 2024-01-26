# API Burguer

Projeto desenvolvido em Node.js . Este projeto é uma API CRUD de uma hamburgueria.

## Scripts disponíveis

No diretório do projeto, você pode executar: `npm run server`, para iniciar o servidor no modo de desenvolvimento.
\
Abra [http://localhost:3001/](http://localhost:3001/) para visualizá-lo em seu navegador.

## Rotas utilizando o Express
- Middleware checkUserId -> Verifica se o ID existe
- Middleware details -> Exibe o método e a URL da requisição
- GET / -> Rota para testar o servidor
- POST /orders -> Adiciona um pedido
- GET /orders -> Lista todos os pedidos
- PUT /orders:id -> Alterar um pedido
- DELETE /orders:id -> Deleta um pedido
- GET /orders:id -> Retorna o pedido especificado
- PATCH /orders:id -> Altera o status para 'Pronto'

## Deployment

Acesse o deploy da aplicação online: [https://burguer-backend.vercel.app](https://burguer-backend.vercel.app)

## Tecnologias

- Node
- Express
- UUID
- Cors
- Git and Github
- Vercel