Company Order Management System
Project Overview
This project is a backend API for a Company Order Management System. The system allows for managing companies, products, product categories, orders, and users. The API will support standard operations such as creating products, placing orders, and registering users. The project is designed to be scalable and extendable, with a focus on maintainability and best practices.

Key Features
Onion Architecture: Ensures a clear separation of concerns and facilitates maintainability.
Repository Design Pattern + CQRS: Provides a structured approach to data access and command/query segregation.
Service Layer: Implements business logic between Repository and Controller.
SOLID Principles: Ensures that the code is scalable, maintainable, and testable.
Dependency Injection: Promotes loose coupling and enhances testability.
Code-First DB Implementation: Utilizes MSSQL, .NET EntityFramework, and LINQ for database operations.
UnitOfWork Pattern: Manages database transactions efficiently.
DTOs for Controllers: Ensures a clear contract between the API and its consumers.
Standardized API Responses: Provides consistent and clear feedback to API consumers.
Unit Testing: Achieves 70% code coverage with unit tests.
Exception Handling System: Provides robust error handling.
Caching: Caches Company and ProductCategory data for improved performance.
Seed Data: Provides initial data for development and testing.

Mail Service: Sends emails using MailKit.
Logger: Implements logging for tracking and debugging.
