# E-Commerce Platform

> A production-oriented, enterprise-grade e-commerce platform built incrementally to learn modern frontend, backend, DevOps, and cloud engineering through real-world implementation.

---

## Project Vision

This project is **not** intended to be a tutorial or demo application.

The goal is to design and build a scalable, maintainable, production-ready e-commerce platform following real software engineering practices.

The project will evolve in multiple phases:

* Angular Admin Portal
* React Customer Storefront
* Spring Boot REST API
* MYSQL Database
* Dockerized Infrastructure
* CI/CD Pipelines
* AWS Deployment

---

# Architecture

This repository follows a **modular monolith** architecture during development.

Initially, all applications live inside a single repository.

```
ecommerce-platform/

├── admin-angular/
├── customer-react/
├── backend-springboot/
│
├── docs/
│   ├── architecture.md
│   ├── roadmap.md
│   ├── api-spec.md
│   └── database.md
│
├── docker/
│
├── .github/
│   └── workflows/
│
├── README.md
└── LICENSE
```

This allows the frontend, backend, infrastructure, and documentation to evolve together while maintaining a single source of truth.

---

# Current Status

## In Progress

* Angular Admin Portal
* Mock REST API
* Production Architecture
* Documentation

## Planned

* React Storefront
* Spring Boot Backend
* mysql
* Docker
* GitHub Actions
* AWS Deployment

---

# Technology Stack

## Frontend

* Angular 21
* TypeScript
* Angular Material
* Angular CDK
* SCSS
* RxJS
* Signals

## State Management

* NgRx Store
* NgRx Effects
* NgRx Entity
* NgRx DevTools

## Rendering

* Angular SSR
* Hydration

## Forms

* Reactive Forms
* Typed Forms
* FormArray
* Custom Validators

## Routing

* Standalone Components
* Lazy Loading
* Route Guards
* Route Resolvers

## Internationalization

* Angular i18n
* Runtime Language Switching

## HTTP

* HttpClient
* Functional Interceptors
* Global Error Handling

## Testing

* Unit Testing
* Component Testing
* Service Testing
* NgRx Testing

## Backend (Planned)

* Spring Boot
* Spring Security
* JWT Authentication
* REST API

## Database (Planned)

* mysql

## Infrastructure (Planned)

* Docker
* Docker Compose
* Nginx

## Cloud (Planned)

* AWS

---

# Development Tools

* Git
* GitHub
* GitHub Desktop
* GitHub Projects
* GitHub Issues
* Visual Studio Code / Android Studio / Antigravity IDE

---

# Code Quality

* ESLint
* Prettier
* Husky
* lint-staged
* Conventional Commits

---

# CI/CD

The project will implement an enterprise-style CI/CD pipeline using GitHub Actions.

## Continuous Integration

* Dependency Installation
* Linting
* Unit Tests
* Build Verification
* Pull Request Validation

## Continuous Delivery

* Production Build
* Docker Image Build
* Docker Image Publishing
* Deployment Automation

## Planned GitHub Actions

* Angular Build
* Unit Tests
* ESLint
* Pull Request Validation
* Release Pipeline
* Docker Build
* Deployment Pipeline

---

# Git Workflow

The project follows a feature branch workflow.

```
main

develop

feature/*

bugfix/*

hotfix/*

release/*
```

Every feature is developed in its own branch and merged using Pull Requests.

---

# Commit Convention

```
feat(products): add product management

feat(auth): implement login

fix(orders): resolve pagination issue

refactor(store): simplify ngrx selectors

test(products): add reducer tests

docs(readme): update documentation

ci(actions): add Angular build workflow
```

---

# Features

## Authentication

* Login
* Logout
* Mock JWT
* Refresh Token Simulation
* Route Guards
* HTTP Interceptors

---

## Dashboard

* Revenue Summary
* Product Statistics
* Order Statistics
* Recent Orders
* Sales Chart

---

## Products

* Product CRUD
* Search
* Sorting
* Pagination
* Filtering
* Categories
* Product Images
* Status Management

---

## Orders

* Order List
* Order Details
* Status Updates

---

## Payments

* Payment History
* Transaction Details
* Payment Status

---

# Non-Functional Features

* Responsive Design
* Dark Mode
* Accessibility
* Loading Indicators
* Skeleton Screens
* Toast Notifications
* Error Handling
* Empty States
* Reusable Components
* Reusable Dialogs

---

# Learning Objectives

This project serves as a practical learning platform for modern software engineering.

## Frontend

* Angular Architecture
* Signals
* NgRx
* RxJS
* Angular Material
* Angular CDK
* Angular SSR
* Hydration
* Reactive Forms
* Angular i18n
* Unit Testing

## Backend

* Spring Boot
* Spring Security
* REST API Design
* JWT Authentication
* mysql

## DevOps

* Git
* GitHub
* GitHub Desktop
* GitHub Actions
* CI/CD
* Docker
* Docker Compose
* Nginx

## Cloud

* AWS Deployment
* Production Hosting
* Environment Configuration

## Engineering

* Clean Architecture
* SOLID Principles
* Modular Design
* Enterprise Folder Structure
* API Design
* Documentation
* Production Debugging

---

# Roadmap

## Phase 1

* Repository Setup
* Documentation
* Angular Project Initialization

## Phase 2

* Authentication
* Dashboard
* Products
* Orders
* Payments

## Phase 3

* Unit Testing
* CI/CD
* Production Optimization

## Phase 4

* React Storefront

## Phase 5

* Spring Boot Backend
* mysql
* JWT Authentication

## Phase 6

* Docker
* Docker Compose
* Nginx

## Phase 7

* AWS Deployment

---

# Future Features

* Discounts
* Coupons
* Inventory Management
* Reviews
* Wishlist
* Notifications
* Analytics Dashboard
* Email Service
* Payment Gateway Integration
* Cloud Image Storage
* Redis Caching

---

# Documentation

Additional documentation is available in the `/docs` directory.

* Architecture
* API Specification
* Database Design
* Development Roadmap

---

# Project Philosophy

* Build production-quality software.
* Learn technologies through implementation.
* Prioritize maintainability over shortcuts.
* Follow enterprise development practices.
* Replace the mock backend with a real backend without changing frontend architecture.
* Keep code clean, modular, testable, and scalable.

---

# License

This project is licensed under the MIT License.
