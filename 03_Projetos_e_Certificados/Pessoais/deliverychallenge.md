# deliverychallenge

## Categoria

Projeto de trabalho / mentoria.

## Resumo

Delivery Challenge e uma aplicacao simples de delivery criada para praticar backend, API REST, persistencia de dados, frontend e integracao por eventos. O escopo cobre um fluxo de MVP com cliente, restaurante, cardapio, criacao de pedidos e evolucao do status do pedido.

## Objetivo

Construir uma solucao fullstack de delivery com arquitetura dividida entre backend, frontend, banco de dados e mensageria, permitindo praticar conceitos usados em sistemas corporativos.

## Tecnologias

- Java 21.
- Quarkus.
- JPA/Hibernate.
- REST Jackson.
- OpenAPI.
- IBM DB2.
- H2 para testes.
- Kafka.
- Docker Compose.
- Angular 17.
- TypeScript.
- CSS.
- GitHub Actions.

## Funcionalidades

- Listagem de cliente, restaurante e cardapio do MVP.
- Criacao de pedidos a partir de um item do cardapio.
- Persistencia de pedidos, historico e status no DB2.
- Evolucao do pedido pelos status `CREATED`, `CONFIRMED`, `PREPARING`, `READY` e `DELIVERED`.
- Publicacao e consumo de eventos via Kafka.
- Frontend com visao de cliente e painel operacional do restaurante.
- Testes automatizados do backend com H2 em memoria.

## Link

[GitHub - delivery-challenge](https://github.com/Marichoii/delivery-challenge)

## Registro

Projeto registrado no Study Hub como evidencia de pratica profissional, mentoria, backend Java, frontend Angular, eventos e integracao com banco de dados.
