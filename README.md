
# WorkShop SpringBoot JPA

🇧🇷
Este é um projeto de exemplo para um sistema de vendas usando Spring Boot. O sistema permite a gestão de produtos, pedidos e usuários, com todas as informações armazenadas em um banco de dados H2 em memória. O projeto demonstra funcionalidades básicas de CRUD (Criar, Ler, Atualizar e Deletar) para todos os principais componentes do sistema.

## Funcionalidades
- **CRUD de Produtos:** Permite a criação, leitura, atualização e exclusão de produtos.
- **CRUD de Pedidos:** Permite a criação, leitura, atualização e exclusão de pedidos.
- **CRUD de Usuários:** Permite a criação, leitura, atualização e exclusão de usuários.
- **Relacionamento entre Entidades:** Os pedidos estão relacionados com os produtos e usuários.
- **Persistência de Dados:** Utiliza o banco de dados H2 para armazenar informações durante a execução da aplicação.

## Tecnologias Utilizadas
- **Spring Boot:** Framework para construção da aplicação.
- **Spring Data JPA:** Abstração de persistência para simplificar o acesso a dados.
- **H2 Database:** Banco de dados em memória para armazenamento temporário dos dados.
- **Spring Web:** Para criação dos endpoints RESTful.

### Endpoints Disponíveis

1. **Produtos:**
   - **GET `/products`**: Lista todos os produtos.
   - **GET `/products/{id}`**: Busca um produto pelo ID.

2. **Pedidos:**
   - **GET `/orders`**: Lista todos os pedidos.
   - **GET `/orders/{id}`**: Busca um pedido pelo ID.

3. **Usuários:**
   - **GET `/users`**: Lista todos os usuários.
   - **GET `/users/{id}`**: Busca um usuário pelo ID.
   - **POST `/users`**: Cria um novo usuário.
   - **PUT `/users/{id}`**: Atualiza um usuário existente.
   - **DELETE `/users/{id}`**: Deleta um usuário pelo ID.

### Exemplos de CRUD:

* Insert:
`{
    "name": "Bob Brown",
    "email": "bob@gmail.com",
    "phone": "977557755",
    "password": "123456" 
}`

* Update:
`{
    "name": "Bob Brown",
    "email": "bob@gmail.com",
    "phone": "977557755"
}`

# WorkShop SpringBoot JPA
🇺🇸
This is an example project for a sales system using Spring Boot. The system allows the management of products, orders and users, with all information stored in an in-memory H2 database. The project demonstrates basic CRUD (Create, Read, Update and Delete) functionalities for all main components of the system.

## Functionalities
- **Products CRUD:** Allows the creation, reading, updating and deletion of products.
- **Oders CRUD:** Allows you to create, read, update and delete orders.
- **Users CRUD:** Allows the creation, reading, updating and deletion of users.
- **Relationship between Entities:** Orders are related to products and users.
- **Data Persistence:** It uses the H2 database to store information during application execution.

## Technologies Used
- **Spring Boot:** Framework for building the application.
- **Spring Data JPA:** Persistence abstraction to simplify data access.
- **H2 Database:** In-memory database for temporary data storage.
- **Spring Web:** For creating RESTful endpoints.

### Available Endpoints

1. **Products:**
   - **GET `/products`**: List all products.
   - **GET `/products/{id}`**: Search for a product by ID.

2. **Oders:**
   - **GET `/orders`**: List all orders.
   - **GET `/orders/{id}`**: Search for an order by ID.

3. **Users:**
   - **GET `/users`**: List all users.
   - **GET `/users/{id}`**: Searches for a user by ID.
   - **POST `/users`**: Creates a new user.
   - **PUT `/users/{id}`**: Updates an existing user.
   - **DELETE `/users/{id}`**: Deletes a user by ID.

### CRUD Examples:

* Insert:
`{
    "name": "Bob Brown",
    "email": "bob@gmail.com",
    "phone": "977557755",
    "password": "123456" 
}`

* Update:
`{
    "name": "Bob Brown",
    "email": "bob@gmail.com",
    "phone": "977557755"
}`
