# Idx Document API

<!---Esses são exemplos. Veja https://shields.io para outras pessoas ou para personalizar este conjunto de escudos. Você pode querer incluir dependências, status do projeto e informações de licença aqui--->

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?logo=java&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?logo=docker&logoColor=white)
[![GitHub forks](https://img.shields.io/github/forks/rafallis/idx-documents)](https://github.com/rafallis/apidocuments/network)
[![GitHub license](https://img.shields.io/github/license/rafallis/idx-documents)](https://github.com/rafallis/apidocuments/blob/main/LICENSE.md)

> API for receice document via RabbitMQ and indexing in elasticsearch

> This project also has a Vue frontend for testing [FRONTEND](https://github.com/rafallis/frontend-apidocuments) and a api to insert documents [ApiDocuments](https://github.com/rafallis/apidocuments)

### Steps

The project is still under development. See above:

- [-] CRUD Document
- [ ] Receive message from RabbitMQ with Document Object
- [ ] Send to elasticsearch indexing
- [ ] Write unit tests

## 💻 Project requirements

* `Maven 3.8`
* `Java 17`
* `Docker | Docker-compose`
* `MySQL 5.6`

## 🚀 Run the Project

Run `docker-compose.yml` to initializae Elastisearch environment:
```
docker-compose up -d
```

Build and run Spring Boot project
```
mvn clean install
mvn spring-boot:run
```

## ☕ Endpoints

UNDER CONSTRUCION

## 📝 License

This project is under GNU GPL V3.0 License [LICENSE](LICENSE.md) for details.

[⬆ Voltar ao topo](#document-api)<br>