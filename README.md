# Spring Boot Social Authorization

### About
Starter code for integrating social logins using GitHub and Google OAuth2.0 as authentication providers. jQuery is used on the front end, Bootstrap for minimal styling. Originally following a Spring tutorial, I've updated the project to use Java 17 from Java 1.8 and Spring Boot 3 from Spring Boot 2.2.2.  

### What I Learned 
- Some methods can no longer be used in newer versions of Java so I had to rebuild my POM file using Java 1.8 and Spring Boot 2.2.2 to follow this tutorial. 
- Using Spring Boot's native OAuth 2.0 support simplified the building of this application. 
- Creating a Client Application that uses the authorization code grant to obtain access tokens from Authorization Servers. 
- Conditional rendering using jQuery for HTML files

### Further Iterations 
- Reorganized the folder structure to follow Spring MVC best practices. 
- Configured the project to connect to MongoDB to save Users to database. 
 
### Technologies
- Java (17)
- Spring Boot (3.0.2)
- Spring Security 
- Maven 
- OAuth2
- ~~JQuery~~ 
- Bootstrap (3.2) 
- Thymeleaf
- HTML

