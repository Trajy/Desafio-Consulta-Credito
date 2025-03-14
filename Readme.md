# DESAFIO TÉCNICO – DESENVOLVIMENTO DE API DE CONSULTA DE CRÉDITOS

#### Este repositório contêm um sistema de arquitetura simples.
#

## Sumário
- [Motivação](#motivação)
- [Executar o Projeto](#executar-o-projeto)

## Motivação

Configurar um ambiente de desenvolvimento utilizando containers Docker e aplicar os seguintes conceitos.

-  Boas Práticas de Código: SOLID ,DRY (Don't Repeat Yourself), KISS (Keep It Simple, Stupid)
  
- Mobile First: Desenvolver interface responsiva para dispositivos móveis.

- Design Patterns: Padrões de projeto Template Method, Strategy no Backend, e Observable no frontend.

- Mensageria: utilizar serviço de processamento de filas (Kafka) para executar tarefas assincronas.


## Executar o Projeto

O sistema foi desenvolvido utilizando arquitetura de containers.
> [!IMPORTANT]
 certifique-se de possuir o [Docker Compose](https://docs.docker.com/compose/) instalado para executar o projeto. 
 
O arquivo[`docker-compose.yml`](./docker-compose.yml) contem todas as declações e configurações necessarias para as aplicações.

execute o comando para iniciar o build e a execução.

```bash
    docker-compose up
```


