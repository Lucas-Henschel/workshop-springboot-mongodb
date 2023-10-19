# Documentação da API 📜
Documentação da API de ligação entre um usuário e post, implementando a arquitetura REST. Abaixo está documentado cada rota que foi criado no projeto.

## End Points

- <h3> Post </h3>

---

- <h3> User </h3>

### List all user

    GET http://localhost:8080/users

#### Response

    Status: 200

    json
    [
      {
        "id": 1,
        "name": "Gabriel",
        "email": "gabriel@gmail.com",
      },
      {
        "id": 2,
        "name": "Maria",
        "email": "maria@gmail.com",
      }
    ]



## 🛠 Tecnologias e Ferramentas

As seguintes tecnoligas e ferramentas foram usadas na construção do projeto:

- **[Java](https://www.java.com/pt-BR/)**
- **[JDK](https://www.oracle.com/br/java/technologies/downloads/)**
- **[MongoDB](https://www.mongodb.com/pt-br/cloud/atlas/lp/try4)**
- **[Spring Boot](https://spring.io/projects/spring-boot)**
- **[Postman](https://www.postman.com/)**
- **[Eclipse](https://eclipseide.org/)**

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://www.linkedin.com/pulse/como-contribuir-em-um-projeto-open-source-github-f%C3%A1bio-amaral/?originalSubdomain=pt)
