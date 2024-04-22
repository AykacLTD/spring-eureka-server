```markdown
# Spring Eureka Server Application

This is a Spring Boot application that serves as a Eureka Server. It is configured to run in different profiles: Istanbul, London, and Paris.
Each profile has a different port number and a different Eureka server name.
To run a specific profile, you can use the following command in the terminal for profile istanbul:

```bash
    mvn spring-boot:run -Dspring-boot.run.profiles=istanbul
```

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Java 17 or higher
- Maven

### Running Project

A step by step series of examples that tell you how to get a development environment running.
1. Navigate into the directory
```bash
cd spring-eureka-server
```
2. Install dependencies
```bash
mvn install
```
3. Run the application
```bash
mvn spring-boot:run -Dspring-boot.run.profiles=profile-name
```

## Deployment

Add additional notes about how to deploy this on a live system.

## Built With

- [Spring Boot](https://spring.io/projects/spring-boot) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency Management

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc
```