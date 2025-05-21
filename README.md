MedicalVoll API 🏥

A RESTful API for a healthcare management system, built with Spring Boot. This project provides endpoints for doctors, patients, appointments, and authentication.
Features ✨
    Doctor & Patient Management (CRUD operations)
    Appointment Scheduling
    JWT Authentication 🔒
    Validation & Error Handling
    Swagger Documentation 📄
Technologies 🛠
    Java 17
    Spring Boot 3
    Spring Security
    JWT (Auth0)
    Hibernate/JPA
    PostgreSQL
    Flyway (Database migrations)
    Lombok
    Swagger/OpenAPI
Setup 🚀
Prerequisites
    Java 17
    PostgreSQL
    Maven
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Installation
1-> Clone the repository:
  git clone https://github.com/gabrielfonseca-de/api-MedicoVoll.git
2 -> Configure PostgreSQL in application.properties:
  spring.datasource.url=jdbc:postgresql://localhost:5432/medvoll  
  spring.datasource.username=your_username  
  spring.datasource.password=your_password  
3 -> Run the application:
  mvn spring-boot:run
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
API Documentation 📚

Access Swagger UI after running the app:
🔗 http://localhost:8080/swagger-ui.html
Endpoints Overview
Method	Path	Description
POST	/auth/login	User authentication
POST	/doctors	Register a new doctor
GET	/doctors	List all doctors
PUT	/doctors/{id}	Update doctor
DELETE	/doctors/{id}	Deactivate doctor

(See Swagger for full details)
License 📜

MIT
---------------------------------------------------------------------------------------------------------------------------------------------------------
Notes:

    Replace placeholder database credentials with your actual PostgreSQL config.

    Adjust paths/descriptions if needed to match your exact API structure.

    For production, recommend adding:

        Environment variables (.env)

        Docker setup instructions
