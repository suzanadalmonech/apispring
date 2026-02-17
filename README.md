# Projeto Spring Boot - API de Gestão de Clientes 🚀

Este projeto é uma API REST moderna desenvolvida com **Java 21** e **Spring Boot**, focada na implementação de padrões de projeto e máxima produtividade utilizando **Lombok**.

## 🛠️ Tecnologias Utilizadas
* **Java 21 (LTS)**: Linguagem principal com as últimas funcionalidades.
* **Spring Boot 3+**: Framework base para agilizar o desenvolvimento.
* **Lombok**: Biblioteca para eliminar código boilerplate (getters, setters, etc.).
* **Maven**: Gerenciador de dependências e automação do projeto.
* **Spring Data JPA**: Para persistência de dados e ORM.
* **H2 Database**: Banco de dados em memória para testes rápidos.
* **OpenAPI / Swagger**: Para documentação e testes das rotas da API.

## 📋 Funcionalidades
* **CRUD de Clientes**: Cadastro, consulta, atualização e exclusão de clientes.
* **Integração com ViaCEP**: Busca automática de endereços a partir do CEP via Feign Client.
* **Padrões de Projeto**: Implementação de **Singleton**, **Strategy** e **Facade**.

## ⚙️ Configuração do Lombok (Obrigatório)
Para o projeto compilar corretamente, sua IDE deve estar configurada:
1. Instale o plugin **Lombok**.
2. Habilite o **Annotation Processing** nas configurações do compilador da sua IDE.

## 🚀 Como Executar o Projeto
1. Clone o repositório.
2. Certifique-se de ter o **JDK 21** instalado.
3. Execute o comando Maven: 
   ```bash
   ./mvnw spring-boot:run
