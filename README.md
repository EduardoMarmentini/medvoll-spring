<!-- Logo da Clínica -->
<p align="center">
  <img src="docs/logo.png" alt="Logo da Clínica" width="200"/>
</p>

<h1 align="center">Backend - Medvoll</h1>

<p align="center">
  Sistema backend desenvolvido com Java Spring Boot para gerenciar atendimentos, agendamentos, pacientes e profissionais de saúde.
</p>

---

## 📋 Descrição

Este projeto é o backend de um sistema completo de gerenciamento para uma clínica médica, desenvolvido com **Java** e **Spring Boot**. Ele fornece uma API RESTful robusta para integração com frontend web e aplicativos móveis, com foco em segurança, escalabilidade e performance.

---

## ✅ Funcionalidades

- [ ] Cadastro e autenticação de pacientes
- [ ] Registro e gerenciamento de profissionais de saúde
- [ ] Agendamento e cancelamento de consultas
- [ ] Controle de prontuários e histórico médico
- [ ] Geração de relatórios e dashboards administrativos
- [ ] Envio de notificações para pacientes via e-mail/SMS
- [ ] Gestão de convênios e pagamentos
- [ ] Área administrativa com controle de permissões e perfis de usuário

---

## 🛠️ Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Data JPA
- Spring Security (JWT)
- Hibernate
- PostgreSQL
- Flyway (versionamento de banco)
- Maven
- Swagger / OpenAPI
- Docker (opcional para ambiente de produção)
- Lombok

---

## 📚 Metodologias e Boas Práticas

- Arquitetura MVC
- Princípios SOLID e Clean Code
- Testes automatizados com JUnit e Mockito
- Versionamento de banco de dados com Flyway
- Integração e entrega contínua (CI/CD)
- API RESTful com tratamento global de exceções
- Autenticação e autorização com JWT
- Uso de DTOs e mapeamentos com ModelMapper

---

## 📦 Dependências Principais

```xml
<dependencies>
  <!-- Spring Boot Starters -->
  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
  </dependency>
  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-jpa</artifactId>
  </dependency>
  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
  </dependency>

  <!-- Banco de Dados -->
  <dependency>
    <groupId>org.postgresql</groupId>
    <artifactId>postgresql</artifactId>
  </dependency>

  <!-- JWT -->
  <dependency>
    <groupId>io.jsonwebtoken</groupId>
    <artifactId>jjwt</artifactId>
    <version>0.9.1</version>
  </dependency>

  <!-- Lombok -->
  <dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <optional>true</optional>
  </dependency>

  <!-- Documentação Swagger -->
  <dependency>
    <groupId>org.springdoc</groupId>
    <artifactId>springdoc-openapi-ui</artifactId>
    <version>1.6.14</version>
  </dependency>

  <!-- Flyway -->
  <dependency>
    <groupId>org.flywaydb</groupId>
    <artifactId>flyway-core</artifactId>
  </dependency>
</dependencies>
```
## 🚀 Como executar o projeto
```bash

# Clone o repositório
git clone https://github.com/seu-usuario/backend-clinica-medica.git

# Acesse o diretório do projeto
cd backend-clinica-medica

# Configure o banco de dados em src/main/resources/application.properties

# Execute o projeto
./mvnw spring-boot:run
```
## 🗂 Estrutura de Pastas
```css
src
├── main
│   ├── java
│   │   └── com.clinica.backend
│   │       ├── config
│   │       ├── controller
│   │       ├── dto
│   │       ├── model
│   │       ├── repository
│   │       └── service
│   └── resources
│       ├── application.properties
│       └── db
│           └── migration
└── test
    └── com.clinica.backend

```
