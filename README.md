# FoodApp
# Notes

## Installation

1. Clone Repo

``` git clone https://github.com/hanan-abdelmaseh/foodApplication.git ```

2. install Dependencies

``` npm install ```

---

## For Each Task
- Create New Branch by task name
``` git branch -b [task name] ```
- Stage Changes
``` git add . ```
- Commit Changes
``` git commit -m "msg" ```
- Pull Request to Remote
``` git push origin [branch name] ```

> keep in mind commiting with understandable message

---

# Architecture

## Core Module
- Core Guards
- Interceptors

## Shared Module
- Shared Components
- Shared Modules

## Major Modules

### Auth Module
- Auth Components
    - Login
    - Register
    - Verify
    - Request Reset
    - Reset
- Auth Service
- Auth Models

### Dashboard Module

Contain Dashboard Sub-Modules

#### User Modules
- Favorites Module
- Receipes Module


#### Admin Modules
- Receipes Module
- Categories Module
- Users Module

---
# Folders Structures

```bash
.
├── core
│   ├── Guards
│   └── interceptors
├── Modules
│   ├── auth
│   │   ├── models
│   │   ├── services
│   │   └── components
│   ├──dashboard
│   ├── Admin
│   │   ├── Users
│   │   ├── Receipes
│   │   └── Categories
│   └── User
│        ├──  Favorites 
│        └── Receipes
├── shared
│   └── components
└── README.md
```

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.11.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
