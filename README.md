# Exercício 01 - Gerenciamento de Livro

API REST com Spring Boot para gerenciamento de livros.

## Tecnologias
- Java 17
- Spring Boot 4.0.4
- Spring Data JPA
- H2 (banco em memória)

## Estrutura de pacotes
```
src/main/java/com/example/aula2/
├── entity/
├── repository/
├── service/
└── controller/
```

## Como executar
```bash
mvn spring-boot:run
```

## H2 Console
Acesse: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:livrosdb
