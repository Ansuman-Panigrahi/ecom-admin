# ecom-admin
admin module of ecommerce app using angular frontend .


# E-Commerce Platform

A production-oriented, enterprise-grade e-commerce platform built incrementally to learn and demonstrate modern full-stack development practices.

> **Current Phase:** Angular Admin Portal (Mock API)

Future milestones include a React storefront, Spring Boot backend, PostgreSQL, Docker, CI/CD, and AWS deployment.

---

# Vision

This project is designed to simulate the architecture and development practices used in real production applications.

The focus is on:

* Clean Architecture
* Scalability
* Maintainability
* Reusability
* Enterprise Development Practices
* Testability
* CI/CD
* Cloud Deployment

---

# Repository Structure

```text
ecommerce-platform/

admin-angular/
customer-react/
backend-springboot/

docs/
docker/

.github/
    workflows/

README.md
```

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
* Custom Validators
* FormArray

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

* Jasmine / Karma *(or Jest if adopted)*
* Unit Testing
* Component Testing
* Service Testing
* NgRx Testing

## Mock Backend

* JSON Server *(initial phase)*

Later:

* Spring Boot REST API

---

# Development Tools

* Git
* GitHub
* GitHub Projects
* GitHub Issues
* VS Code

---

# Code Quality

* ESLint
* Prettier
* Husky
* lint-staged
* Conventional Commits

---

# CI/CD

The project will implement a production-style CI/CD pipeline using GitHub Actions.

## Continuous Integration

* Automatic dependency installation
* Linting
* Unit Tests
* Build Verification
* Pull Request Validation

## Continuous Delivery

* Production Build
* Docker Image Build
* Docker Image Publish *(future)*
* Automatic Deployment *(future)*

## GitHub Actions (Planned)

* Angular Build Workflow
* Unit Test Workflow
* Lint Workflow
* Pull Request Checks
* Release Workflow
* Docker Build Workflow
* Deployment Workflow

---

# Git Workflow

This project follows a feature branch workflow.

```text
main
develop

feature/*
bugfix/*
hotfix/*
release/*
```

Every feature is developed using Pull Requests before merging.

---

# Commit Convention

Examples:

```text
feat(products): add product management

feat(auth): implement login

fix(orders): resolve pagination issue

refactor(store): simplify ngrx selectors

test(products): add reducer tests

docs(readme): update project documentation

ci(actions): add Angular build pipeline
```

---

# Features (Version 1)

## Authentication

* Login
* Logout
* Mock JWT
* Route Guards
* Refresh Token Simulation

## Dashboard

* Sales Overview
* Revenue
* Orders
* Product Statistics

## Products

* CRUD
* Search
* Sort
* Filters
* Pagination
* Product Images
* Categories

## Orders

* Order List
* Order Details
* Status Updates

## Payments

* Payment History
* Transaction Details
* Payment Status

---

# Non-Functional Features

* Responsive Design
* Dark Mode
* Accessibility
* Loading States
* Skeleton Loaders
* Error Pages
* Empty States
* Toast Notifications
* Reusable Components
* Global Error Handling

---

# Learning Objectives

This project is also intended to gain practical experience with:

* Angular Architecture
* NgRx
* SSR & Hydration
* RxJS
* Unit Testing
* Git
* GitHub
* GitHub Actions
* CI/CD
* Docker
* Docker Compose
* Spring Boot
* Spring Security
* PostgreSQL
* REST API Design
* AWS Deployment
* Nginx
* Production Debugging
* Monitoring & Logging
* Software Architecture
* Enterprise Development Practices

---

# Future Roadmap

## Frontend

* React Customer Store

## Backend

* Spring Boot
* Spring Security
* JWT Authentication
* PostgreSQL

## Infrastructure

* Docker
* Docker Compose
* GitHub Actions
* AWS
* Nginx

## Future Features

* Discounts
* Coupons
* Inventory
* Reviews
* Wishlist
* Notifications
* Analytics
* Payment Gateway
* Cloud Storage
* Redis Caching

---

# Project Goal

The objective is to build a scalable, maintainable, production-ready e-commerce platform while learning modern frontend, backend, DevOps, and cloud technologies through real-world implementation rather than isolated tutorials.
