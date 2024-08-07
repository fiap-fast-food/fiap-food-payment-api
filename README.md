# fiap-food-payment

Microserviço responsável pelo gerenciamento de pagamentos dos pedidos na lanchonete de autoatendimento.

## Descrição

Este microserviço faz parte da arquitetura de microsserviços do projeto de autoatendimento de fast food. Ele gerencia os pagamentos dos pedidos, registrando a solicitação de pagamento, recebendo o retorno do processador de pagamento e atualizando o status do pedido.

## Funcionalidades

- Recebimento de solicitações de pagamento.
- Processamento de pagamentos.
- Atualização do status do pagamento.
- Integração com outros microsserviços para sincronização de dados.

## Requisitos

- Java 17
- Maven 3.8.5+
- Docker

## Tecnologias Utilizadas

- Spring Boot
- Spring Data JPA
- PostgreSQL
- Docker
- OpenAPI (Swagger)

## Estrutura do Projeto

O projeto segue a seguinte estrutura de diretórios:

## Endpoints Principais

json
{
"orderId": "123456",
"amount": 50.0,
"paymentMethod": "CREDIT_CARD"
}


json

{
"status": "CONFIRMED"
}
