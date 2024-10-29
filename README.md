# JAVA FULL STACK : ROLE BASED AUTHENTICATION

# DISCRIPTION :

  This project implements a role-based authentication (RBAC) system, allowing user registration, login, and access control based on user roles. 
  It is developed using Spring Boot for the backend, which provides JWT-based authentication, and React for the frontend, which handles the user interface and role-specific dashboards.
  The main goal is to ensure secure access to resources according to user roles. 

# FEATURES :
 - USER REGISTRATION / LOGIN
 - JWT Authentication
 -  Role-Based Access Control
 -  Role-Specific Dashboards
   
#  INTILIZATION
- Install  the VISUAL STUDIO CODE from >> https://code.visualstudio.com/docs/?dv=win64user
_ Instal  JDK  from >> https://download.oracle.com/java/23/latest/jdk-23_windows-x64_bin.exe (sha256)
-  Go to the browser from >>https://start.spring.io
-  Select  the  Project  : Maveen
                Language : JAVA
                Springboat version : 3.3.5
                 Packing : jar
                           java version 17
- Add the Dependencies :
               *Spring Web 
               *Spring data JPA 
                *Spring Boot Dev tool
                *Spring Security
                * My sql Driver
  -GENERATE THE FILE
   - FILE IS DOWNLOADING ON ZIP
   - THE ZIP FILE Extract to the visual studio Code
 
#  Usage :
# Project Structure:
src
main
java
com
example
OJT
OjtApplication.java // main method class
config >> AppConfig.java >> SecurityConfig.java // Spring Security configuration >> WebSecurityConfigurerAdapter.java
controllers >> UserController.java // REST controller for authentication
models >> User.java // User entity
repository >> UserRepository.java // User repository interface
service >> UserService.java // User service class
utils >> JwtUtil.java // JWT utility class
filter >> JwtAuthenticationFilter.java
resources >> application.properties
By using this project structure develop the backend application
Run the OjtApplication.java file, the Spring Boot application will starts.
# Environment Variables:
DATABASE_URL= jdbc:mysql://localhost:3306/rbac_db
JWT_SECRET= sS0RJc6PNefnp+2awVYXxYNnDW2EAwavBO4ZCRCJEX4=
  
# lisence

                   
 





