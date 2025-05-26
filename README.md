# Spring Boot MongoDB

Este projeto é uma aplicação Java utilizando Spring Boot e MongoDB, demonstrando operações básicas de CRUD (Create, Read, Update, Delete) com integração ao banco de dados NoSQL MongoDB.

## 🚀 Tecnologias Utilizadas

* ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=java\&logoColor=white) Java 17+
* ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge\&logo=spring-boot\&logoColor=white) Spring Boot
* ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge\&logo=mongodb\&logoColor=white) MongoDB
* ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge\&logo=apache-maven\&logoColor=white) Maven

## ⚙️ Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

* [Java 17 ou superior](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
* [Maven](https://maven.apache.org/install.html)
* [MongoDB](https://www.mongodb.com/try/download/community)

## 📆 Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/NoClick11/spring-boot-mongodb.git
   cd spring-boot-mongodb
   ```

2. Configure o MongoDB:

   Certifique-se de que o MongoDB está em execução na porta padrão (27017).

3. Instale as dependências e compile o projeto:

   ```bash
   mvn clean install
   ```

## ▶️ Execução

Para iniciar a aplicação:

```bash
mvn spring-boot:run
```

A aplicação estará disponível em `http://localhost:8080`.

## 📁 Estrutura do Projeto

```plaintext
spring-boot-mongodb/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── springbootmongodb/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               └── repository/
│   │   └── resources/
│   │       └── application.properties
├── pom.xml
```

* `controller/`: Contém os controladores REST.
* `model/`: Define as entidades do MongoDB.
* `repository/`: Interfaces para acesso aos dados.
* `application.properties`: Configurações da aplicação.

## 🥺 Testes

Para executar os testes:

```bash
mvn test
```

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
