# DESAFIO TÉCNICO – DESENVOLVIMENTO DE API DE CONSULTA DE CRÉDITOS

## Sumário
  - [Git Submodules](#git-submodules)
  - [Motivação](#motivação)
  - [Executar o Projeto](#executar-o-projeto)

## Git Submodules
A fim de manter uma maior organização na estrutura do projeto o frontend e o backend foram divididos em submodulos (outros repositórios) mantendo o código de cada aplicação em seu respectivo repositorio. Esta documentação possui as motivações e instruções para execução do ambiente para o sistema. Para mais detalhes sobre as implementações do frontend e backend vide as documentações

- Frontend: [Consulta Crédito Web](https://github.com/Trajy/Consulta-Credito-Web)
- Backend: [Consulta Crédito Api](https://github.com/Trajy/Consulta-Credito-Api)

> [!IMPORTANT]
> Ao baixar este repositório os submodulos serão baixados automaticamente.

## Motivação

Configurar um ambiente de desenvolvimento utilizando containers Docker e aplicar os seguintes conceitos.

-  Boas Práticas de Código: SOLID ,DRY (Don't Repeat Yourself), KISS (Keep It Simple, Stupid)
  
- Mobile First: Desenvolver interface responsiva para dispositivos móveis.

- Design Patterns: Padrões de projeto Template Method, Strategy no Backend, e Observable no frontend.

- Mensageria: utilizar serviço de processamento de filas (Kafka) para executar tarefas assincronas.

Foi desenvolvido um modelo de sistema simples, conforme o diagrama.

>[!NOTE] 
Para fins demonstrativos o Producer e o Consumer do serviço de mensageria estão na mesma api.

![image](./docs/img/Simple%20Architecture.jpeg)


## Executar o Projeto

O sistema foi desenvolvido utilizando arquitetura de containers.
>[!IMPORTANT]
 certifique-se de possuir o [Docker Compose](https://docs.docker.com/compose/) instalado para executar o projeto. 
 
O arquivo[`docker-compose.yml`](./docker-compose.yml) contem todas as declações e configurações necessarias para as aplicações.

execute o comando para iniciar o build e a execução.

```bash
    docker-compose up
```


