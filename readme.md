# 🌱 Spring API

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.1-green)
![Java](https://img.shields.io/badge/Java-21-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)

Este repositório contém uma API REST desenvolvida com **Spring Boot**, utilizando **JPA**, **PostgreSQL**, **Lombok** e **Flyway** para gerenciamento de banco de dados.

---

## 🚀 Tecnologias Utilizadas
- **Spring Boot 3.4.1**
- **Java 21**
- **Maven**
- **JPA / Hibernate**
- **PostgreSQL**
- **Lombok**
- **Flyway**

---

## 📌 Como Rodar o Projeto

### ✅ Pré-requisitos
Antes de iniciar, certifique-se de ter os seguintes itens instalados:
- **Java 21**
- **Maven**
- **PostgreSQL**

### 🔧 Configuração do Banco de Dados
1. Crie um banco de dados no PostgreSQL.
2. Configure as credenciais no arquivo `application.properties` ou `application.yml`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   ```

### ▶️ Executando o Projeto
Para rodar a aplicação, utilize os seguintes comandos no terminal:
```sh
mvn clean install
mvn spring-boot:run
```

---

## 🛠 Endpoints da API
A API fornece endpoints REST para manipulação de dados. Para testar, utilize ferramentas como **Postman** ou **Swagger**.

---

## 📂 Estrutura do Projeto
```
/springapi
│-- src/main/java/com/exemplo/api
│   │-- controllers
│   │-- services
│   │-- repositories
│   │-- models
│-- src/main/resources
│   │-- application.properties
│   │-- db/migration (scripts SQL do Flyway)
```

---

## 📝 Migrações do Banco
O projeto utiliza **Flyway** para gerenciar versões do banco de dados. Para aplicar as migrações, execute:
```sh
mvn flyway:migrate
```

---

## 🤝 Contribuição
Sinta-se à vontade para contribuir com melhorias! Para isso:
1. Faça um **fork** do repositório
2. Crie uma nova **branch**
3. Envie um **pull request**

📌 **Desenvolvido por [Tecoquinho](https://github.com/Tecoquinho) 🚀**

