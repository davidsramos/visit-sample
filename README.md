# POC Multi Module Spring Boot + Angular 8 Maven Build Packing on Regular Java War Files
From time to time it is necessary to distribute SPA applications using war files as containers. 

### Testing Angular Application
To test this build, we could execute `npm run buildProduction`. At webproject's root (`/fivisit-ui`)

### Run the Application
Now it's all yours.
Run `mvn clean install` from the project root directory.
Our configuration should:
- Install NodeJS (and NPM).
- Install JS dependencies.
- Invoke our new hook.
- Copy the result to our final distributable war.

To run the Spring Boot application using Maven, run the following command from the fivisit-api directory:
`mvn spring-boot:run`

Once the application has started, we should be able to see the index.html in the logs, and open the browser navigate to http://localhost:8080/index.html to see the welcome page.
