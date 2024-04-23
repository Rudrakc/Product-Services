# Product Service Project

This project is a learning endeavor aimed at mastering Spring Boot and MySQL database integration. Additionally, it incorporates the usage of MySQL Workbench for database management. The project also includes a FakeStore service, which interacts with FakeStore APIs.

## Features

- **Product Service**: Implements CRUD (Create, Read, Update, Delete) operations for managing products.
- **MySQL Integration**: Utilizes MySQL database for persistent storage of product data.
- **MySQL Workbench**: Provides a graphical interface for managing the MySQL database.
- **FakeStore Service**: Interacts with FakeStore APIs to fetch product information.

## Prerequisites

Before running the project, ensure the following dependencies are installed:

- Java Development Kit (JDK)
- Spring Boot
- MySQL database server
- MySQL Workbench
- Dependencies specified in `pom.xml`
- Your favorite IDE (Eclipse, IntelliJ IDEA, etc.) or text editor.

## Installation

To install and run the project locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Rudrakc/Product-Service.git
   ```

2. Import the project into your preferred IDE (e.g., IntelliJ IDEA, Eclipse).

3. Configure MySQL database settings in `application.properties`.

4. Build the project using Maven:

   ```bash
   mvn clean install
   ```

5. Run the application:
    ```bash
    java -jar target/product-service.jar
   ```


## Usage

- Access the endpoints provided by the Product Service to perform CRUD operations on products.
- Utilize MySQL Workbench to manage the database schema and data.
- Explore the FakeStore Service to interact with FakeStore APIs for fetching product information.

## Endpoints

- `GET /products`: Retrieve all products.
- `GET /products/{id}`: Retrieve a product by ID.
- `POST /products`: Create a new product.
- `PUT /products/{id}`: Update an existing product.
- `DELETE /products/{id}`: Delete a product.
- and many more...


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.



