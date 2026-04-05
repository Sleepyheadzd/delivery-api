# Delivery Tech API

Sistema de delivery desenvolvido com Spring Boot e Java 26.

## 🚀 Tecnologias
- **Java 26**
- Spring Boot 3.4.x
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## ⚡ Recursos Modernos Utilizados
- Records (Java 14+)
- Text Blocks (Java 15+)
- Pattern Matching (Java 17+)
- Virtual Threads (Java 21+)

## 🏃‍♂️ Como executar
1. **Pré-requisitos:** JDK 26 instalado
2. Clone o repositório
3. Execute: `./mvnw spring-boot:run`
4. Acesse: http://localhost:8080/health

## 📋 Endpoints
- GET /health - Status da aplicação
- GET /info - Informações da aplicação
- GET /h2-console - Console do banco H2
- POST /clientes - Cadastrar cliente
- GET /clientes - Listar clientes
- GET /clientes/{id} - Buscar cliente
- PUT /clientes/{id} - Atualizar cliente
- DELETE /clientes/{id} - Inativar cliente
- POST /restaurantes - Cadastrar restaurante
- GET /restaurantes - Listar restaurantes
- GET /restaurantes/categoria/{categoria} - Buscar por categoria
- POST /produtos - Cadastrar produto
- GET /produtos/restaurante/{id} - Produtos por restaurante
- POST /pedidos - Criar pedido
- GET /pedidos/cliente/{id} - Pedidos por cliente
- PATCH /pedidos/{id}/status - Atualizar status

## 🔧 Configuração
- Porta: 8080
- Banco: H2 em memória (deliverydb)
- Profile: development

## 👨‍💻 Desenvolvedor
Sleepy - Turma 04018
Desenvolvido com JDK 26 e Spring Boot 3.4.x