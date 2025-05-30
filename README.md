# Spring Boot + MongoDB CRUD API

Este projeto é uma aplicação Spring Boot que implementa uma API RESTful para operações CRUD com o banco de dados MongoDB. Ele foi desenvolvido com foco em simplicidade, extensibilidade e boas práticas.

## 🚀 Tecnologias Utilizadas

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

## ⚙️ Pré-requisitos

* [Java 17 ou superior](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
* [Maven](https://maven.apache.org/install.html)
* [MongoDB](https://www.mongodb.com/try/download/community)
* [Postman](https://www.postman.com/downloads/)

## 📆 Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/NoClick11/spring-boot-mongodb.git
   cd spring-boot-mongodb
   ```

2. Inicie o MongoDB localmente (por padrão na porta 27017).

3. Compile o projeto:

   ```bash
   mvn clean install
   ```

## ▶️ Execução

Para iniciar a aplicação:

```bash
mvn spring-boot:run
```

A aplicação estará acessível em `http://localhost:8080`

## 🛠️ Funcionalidades

* Criar usuários
* Listar todos os usuários
* Buscar usuário por ID
* Atualizar usuário
* Deletar usuário

## 📝 Exemplos de Uso da API

### 🌐 Criar Usuário (POST /user)

```http
POST /user
Content-Type: application/json

{
  "name": "João da Silva",
  "email": "joao@email.com"
}
```

### 📃 Listar Todos os Usuários (GET /user)

```http
GET /user
```

### 📄 Buscar Usuário por ID (GET /user/{id})

```http
GET /user/664e2278eb7c3e3b9abfcd98
```

### 🔄 Atualizar Usuário (PUT /user/{id})

```http
PUT /user/664e2278eb7c3e3b9abfcd98
Content-Type: application/json

{
  "name": "João da Silva Atualizado",
  "email": "joao.novo@email.com"
}
```

### ❌ Deletar Usuário (DELETE /user/{id})

```http
DELETE /user/664e2278eb7c3e3b9abfcd98
```

## 📁 Estrutura do Projeto

```plaintext
spring-boot-mongodb/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/springmongodb/
│   │   │       ├── controller/
│   │   │       ├── model/
│   │   │       ├── repository/
│   │   │       └── service/
│   │   └── resources/
│   │       └── application.properties
├── pom.xml
```

## 🥺 Testes

Para executar os testes:

```bash
mvn test
```

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias ou correções.
