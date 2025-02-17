# Simple Spring Boot Application - A Quick Start Guide

This project provides a straightforward approach to developing Spring-based applications 
with minimal configuration. It offers default settings and annotations to quickly start 
new Spring projects. Spring Boot automatically configures the necessary classes based on the 
libraries present in the classpath.

## Ways to Create a Spring Boot Application

1. Spring Boot Initializr Web Interface: Use the online tool to generate a project with your 
desired settings.
2. Spring Boot CLI: Utilize the command-line interface for rapid development.
3. Spring Tool Suite (STS) IDE: Leverage the integrated development environment tailored for
Spring applications.

## Key Features

- Exception Handling:
    - `@ExceptionHandler`: Handles exceptions in specific controller methods.
    - `@ControllerAdvice` and `@RestControllerAdvice`: Global exception handling across controllers.
- Response Management:
    - `@ResponseBody`: Directly returns data in the response body.
- Configuration:
    - `application.yaml`: Centralized configuration file.
    - `@Configuration` and `@Bean`: Define and manage beans.
    - `@Value` and `@ConfigurationProperties`: Inject configuration properties.
- Dependency Injection:
    - `@Autowired`: Injects dependencies automatically.
    - `@Qualifier` and `@Primary`: Resolve bean conflicts.
- Component Stereotypes:
    - `@Component`, `@Service`, `@Repository`: Define Spring-managed components.
- Interceptors:
    - `HandlerInterceptor`: Intercepts HTTP requests for preprocessing.

## Getting Started

Prerequisites

Java Development Kit (JDK): Ensure you have JDK 8 or higher installed.
Maven: Used for building and managing the project.
