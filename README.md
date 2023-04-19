# Spring Books - Hello GraphQL

This is a GraphQL project that will introduce you to a simple GraphQl server wuth spring boot. 
The Spring Boot application uses Spring for GraphQL and creates a single endpoint at `/graphql` for all GraphQL queries.
If you want to test out the application you can use the GraphiQL UI located at http://localhost:8080/graphiql

If you want to learn more you can check out my Intro to Spring for GraphQL article over on my blog: 

https://medium.com/@shrutiebony/graphql-what-why-how-and-who-420080903bf4?source=friends_link&sk=9391edad4c2c39c07a7dcb75be0b85c9
## Development 

- Run the Spring Boot application which will run on port 8080

## Packaging 

The Maven plugin maven-resources-plugin will copy the contents of the build directory into `/target/static/classes`. 
Once the artifact has been created you can run the application using the following command: 

` java -jar target/spring-books-0.0.1-SNAPSHOT.jar`
