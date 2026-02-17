# Projeto Spring Boot - API de Gestão de Clientes 🚀

Este projeto é uma API REST desenvolvida com Java e Spring Boot para demonstrar a implementação de padrões de projeto e boas práticas de desenvolvimento.

## 🛠️ Tecnologias Utilizadas
* **Java 17**: Linguagem principal.
* **Spring Boot**: Framework para agilizar o desenvolvimento.
* **Maven**: Gerenciador de dependências e automação do projeto.
* **Spring Data JPA**: Para persistência de dados.
* **H2 Database**: Banco de dados em memória para testes.
* **OpenAPI / Swagger**: Para documentação e testes das rotas da API.

## 📋 Funcionalidades
* **CRUD de Clientes**: Cadastro, consulta, atualização e exclusão de clientes.
* **Integração com ViaCEP**: Busca automática de endereços a partir do CEP.
* **Padrões de Projeto**: Implementação de Singleton, Strategy e Facade.

## 🚀 Como Executar o Projeto
1. Clone o repositório.
2. Certifique-se de ter o Java 17 instalado.
3. Execute o comando Maven: `./mvnw spring-boot:run` ou rode a classe `TestandoApplication.java` no seu editor.
4. Acesse o Swagger para testar as rotas em: `http://localhost:8080/swagger-ui.html`.

## 📁 Estrutura de Pastas
* `controller`: Onde ficam os endpoints da API.
* `model`: Classes que representam as entidades do banco de dados.
* `service`: Lógica de negócio e interfaces.
* `repository`: Interfaces para comunicação com o banco de dados.
