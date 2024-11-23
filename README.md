## About the Project
- This project is a Spring Boot-based CRUD application designed to manage Categories and Products with the following features:                 
- RESTful APIs for performing CRUD operations.
- One-to-Many Relationship: A category can have multiple products.
- Pagination Support: Server-side pagination for listing categories and products.
- Database Integration: Configured with MySQL using JPA and Hibernate.

## Key Features
- CRUD Operations for Categories and Products.
- Database: Uses a relational database (MySQL) instead of an in-memory database.
- Annotation-based Configuration: Eliminates the need for XML configurations.
- Pagination: Supports pagination in API responses.
- Clean Architecture with separate layers:
- Controller: Handles HTTP requests.
- Service: Contains business logic.
- Repository: Manages database interactions.

## Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Postman
- Maven 


# Author
This project was created by **Sushant Narale**, 
Feel free to connect with me on:
- **LinkedIn:** [linkedin.com/in/sushant-narale-771775200](https://www.linkedin.com/in/sushant-narale-771775200/) 
- **GitHub:** [github.com/Sushantnarale](https://github.com/Sushantnarale)
- **Email:** [sushantnarale4785@gmail.com](mailto:sushantnarale4785@gmail.com)

## Folder Structure

```plaintext
spring-boot-crud-example/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── example/
│   │   │   │   │   ├── category/
│   │   │   │   │   │   ├── Category.java                           // Entity class for Category
│   │   │   │   │   │   ├── CategoryRepository.java                 // Repository for Category
│   │   │   │   │   │   ├── CategoryService.java                    // Service layer for Category
│   │   │   │   │   │   ├── CategoryController.java                 // REST controller for Category
│   │   │   │   │   ├── product/
│   │   │   │   │   │   ├── Product.java                            // Entity class for Product
│   │   │   │   │   │   ├── ProductRepository.java                  // Repository for Product
│   │   │   │   │   │   ├── ProductService.java                     // Service layer for Product
│   │   │   │   │   │   ├── ProductController.java                  // REST controller for Product
│   │   │   │   │   ├── SpringBootCrudExampleApplication.java       // Main Application
│   │   │   │   │   ├── config/
│   │   │   │   │   │   ├── AppConfig.java                          // Custom configurations
│   │   ├── resources/
│   │   │   ├── application.properties                              // DB & Server Configurations
