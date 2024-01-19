
  <h1><p align="center"><b><b>Login and Signup Backend API with Spring Boot</b></b>
</p></h1>

<div align="center">

  <a href="">![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)</a>
  <a href="">![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)</a>
  <a href="">![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)</a>
</div>



## Understanding Problem Statement

Developing a secure backend for a REST API using the Spring Boot framework and H2 database is the task at hand. The API should comprise endpoints for user login and signup functionalities, with the former verifying user credentials and generating a JSON Web Token (JWT) upon successful authentication. The signup endpoint should facilitate the creation of new accounts, securely storing user information in the H2 database. An additional hello endpoint is required, accessible post-authentication, responding with the message "Hello from GreenStitch." Security measures, including web tokens for authentication and authorization, must be implemented to protect user data and restrict access to authorized users. The H2 database is employed to securely store user account information, necessitating careful schema design for secure data storage.




## Tech Stack Used

    Java
    Spring Boot
    H2 Database
    Spring Security
    JWT Token
    Lombok
    Maven
    Swagger-UI




## Set Up For Development

```
Prerequisites
- Java Development Kit (JDK) 8 or later
- Maven
- Postman (for testing the API)
```


### Install packages or API:

# 1. Clone the Repository

# 2. Go to directory
   ```
cd Java_Rest_API
```

### Start Local Server For API Testing:

```
./mvnw spring-boot:run
```

### Validation 

```
    Full Name:
        Minimum length: 3 characters
        Maximum length: 20 characters
    Password:
        At least 8 characters
        Contains at least one digit
        Contains at least one lowercase letter
        Contains at least one uppercase letter
        Contains at least one special character
    Email:
        Valid email format
```

### Development

```

The project can be run using an IDE like VS Code.

```

