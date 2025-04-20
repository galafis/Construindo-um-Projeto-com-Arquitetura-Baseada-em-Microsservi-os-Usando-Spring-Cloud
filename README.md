# Projeto Dio Experts Config (SANTANDER BOOTCAMP FULLSTACK DEVELOPER)

Este projeto demonstra como configurar uma arquitetura de microsserviços usando Spring Cloud, Eureka, Config Server e API Gateway.

## Estrutura

- **Config Server**: Centraliza as configurações dos serviços.
- **Service Discovery (Eureka)**: Registro e descoberta de microsserviços.
- **API Gateway**: Entrada unificada para as requisições.

## Execução

Cada módulo possui seu próprio `application.yml` com as portas e nomes definidos. Inicie os projetos na seguinte ordem:

1. **Config Server**
2. **Service Discovery**
3. **API Gateway**
4. **Demais serviços (clientes)**

Todos os arquivos `.yml` estão prontos para uso e podem ser customizados conforme sua organização.

Criado por mim, um futuro cientista de dados, apaixonado por tecnologia. Utilizando fontes fornecidas pelo https://github.com/oswaldoneto/dio-experts-config , consegui cumprir com mais um desafio proposto por esse maravilhoso bootcamp!
