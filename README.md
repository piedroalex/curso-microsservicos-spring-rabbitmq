# curso-microsservicos-spring-rabbitmq

# Projeto: alurafood

Desenvolvido durante o curso [Microsserviços na prática: mensageria com RabbitMQ](https://www.alura.com.br/curso-online-microsservicos-pratica-mensageria-rabbitmq) da Alura.

## Descrição

Sistema de delivery com serviços para realizar pedidos e pagamentos.

## Links dos repositórios:
- [rabbitmq](https://github.com/piedroalex/rabbitmq-docker)
- [server](https://github.com/piedroalex/server)
- [gateway](https://github.com/piedroalex/gateway)
- [pedidos](https://github.com/piedroalex/pedidos)
- [avaliacao](https://github.com/piedroalex/avaliacao)
- [pagamentos](https://github.com/piedroalex/pagamentos)

## Pré-Requisitos

- [x] [Java](https://www.java.com/pt-BR/download/manual.jsp)
- [x] [MySQL](https://dev.mysql.com/downloads/)
- [x] [Docker](https://www.docker.com/products/docker-desktop/)
- [x] [Postman](https://www.postman.com/downloads/)

## Como rodar as aplicações (Em ordem de execução)

### RabbitMQ
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o arquivo, execute o comando: ```docker-compose up```
4. Acessar pelo endereço [http://localhost:15672](http://localhost:15672)
5. Para logar, inserir as credenciais que estão no arquivo yml

### Server
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o projeto, execute o comando: ```./mvnw spring-boot:run```

### Gateway
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o projeto, execute o comando: ```./mvnw spring-boot:run```

### Avaliação
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o projeto, execute o comando: ```./mvnw spring-boot:run```

### Pedidos
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o projeto, execute o comando: ```./mvnw spring-boot:run```

### Pagamentos
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o projeto, execute o comando: ```./mvnw spring-boot:run```
4. Utilizando o Postman, fazer requisições para os endpoints implementados
