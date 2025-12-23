# 🛒 E-commerce Product Catalog Service

## 📌 Overview

This project implements a Product Catalog backend service for an e-commerce platform.
It is responsible for managing core catalog data such as products, categories, and pricing, and exposes RESTful APIs that can be consumed by frontend applications or other backend services (Cart, Order, Search).

The focus of the project is on clean backend architecture, domain modeling, and scalability readiness, rather than UI or traffic simulation.

## 🧱 Architecture

The application follows a layered Spring Boot architecture:

Controller Layer – Handles HTTP requests and API contracts

Service Layer – Contains business logic and validations

Repository Layer – Manages persistence using ORM abstractions

Domain Models – Represent core e-commerce entities

This separation ensures maintainability, testability, and extensibility.

## 🔑 Key Features

Manage products, categories, and pricing

Clean RESTful API design

Well-defined domain models

Stateless service design for scalability

Easily extensible for future features

## ⚙️ Tech Stack

Java

Spring Boot

Spring Data JPA

REST APIs

Relational Database (configurable)

## 📡 API Capabilities (High Level)

The service supports operations such as:

Creating and retrieving products

Organizing products by category

Managing pricing information

Listing catalog data for client consumption

Note: The APIs are designed to be easily extended with pagination, sorting, filtering, and search.

## 📈 Scalability & Design Considerations

Designed as a stateless REST service, enabling horizontal scaling

Suitable for read-heavy workloads, common in catalog systems

Can be independently scaled from other e-commerce services

Ready for integration with caching (e.g., Redis) and search systems

## 🚀 Possible Enhancements

Pagination and sorting for large catalogs

Search and filtering support

Caching layer for frequently accessed data

Integration with inventory and order services

API documentation using Swagger/OpenAPI

## 🧠 What This Project Demonstrates

Strong backend engineering fundamentals

Understanding of real-world e-commerce domains

Clean service and data modeling

Production-ready architecture mindset

## ▶️ How to Run

Clone the repository

Configure database properties in application.properties

Run the Spring Boot application

Access APIs via a REST client (Postman / curl)
