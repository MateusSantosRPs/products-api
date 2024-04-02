O projeto demonstra a criação de uma API RESTful seguindo o método de Leonard Richardson, utilizando 4 níveis para padronização e desenvolvimento:

Níveis:

- POX (Plain Old XML): Comunicação via HTTP sem regras para métodos.
- Recursos: Modelagem da API com recursos (substantivos no plural).
- Verbos HTTP: Uso correto de verbos como GET, POST, PUT e DELETE.
- HATEOAS (Hypertext As The Engine Of Application State): Fornecimento de links para navegação entre recursos.
 

# Desenvolvimento da Products-API:

Base de dados: PostgreSQL.

Camadas:

Models: Lógica da aplicação e regras de negócio.

DTOs: Transferência de dados entre subsistemas.

Controllers: Recebimento de requisições do usuário.

Repositories com JPA: Interface para acesso e persistência de dados com JPA.

Benefícios:

Padronização e melhor organização da API.

Desenvolvimento mais eficiente e escalável.

Maior clareza e facilidade de uso para os consumidores da API.

### Tecnologias Utilizadas
![Spring Boot 3](https://img.shields.io/badge/Spring_Boot_3-%236DB33F?style=for-the-badge&logo=spring-boot&logoColor=black)&nbsp;
![Java](https://img.shields.io/badge/Java_17-060606?style=for-the-badge&logo=openjdk&logoColor=white)&nbsp;
![Maven]( https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)&nbsp;
![Postgres](https://img.shields.io/badge/postgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)&nbsp;

Dependências:
- Spring Web MVC.  
- Spring Data JPA. 
- Spring Validation.
- Spring Halteoas.
