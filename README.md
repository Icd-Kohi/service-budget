# Service Budget Manager
Manage your budgets: Create, Delete, Edit and Generate PDF of your budgets.

A register/login, configure company data, manage reusable service items, create budgets, edit saved budgets, delete saved budgets, and download it as PDF.

------------------

#### Project flow diagram

![](./diagram.png)

```
Login -> Dashboard -> CompanyProfile -> CreateBudget -> FillClientData -> AddItems -> ApplyDiscount -> Generate PDF.
```

#### Entities

```
    User    (1 -> 1) Company
    User    (1 -> N) Budgets
    Budgets (1 -> 1) BudgetItems
    Budgets (N -> 1) Client
```
------------------

#### Routes

*Controller Routes:*
```
        GET    /api/budgets
        POST   /api/budgets
        GET    /api/budgets/{id}
        PUT    /api/budgets/{id}
        DELETE /api/budgets/{id}
        GET    /api/budgets/{id}/pdf
```
        
*Auth Routes (also for Angular and Mobile):*
```
        POST /api/auth/register
        POST /api/auth/login
        Return: { "token": "jwt_token" }
```

------------------

#### Stack

Angular
  - @OpenPDF 1.3.39
  
Spring
  - Spring Web
  - Spring Data JPA
  - Spring Security
  - PostgreSQL Driver
  - Validation
  - Lombok
  
PostgreSQL 18

------------------

#### Requirements

- Java 17+
- Maven
- Node.js
- Docker with Compose plugin
- PostgreSQL container

------------------

#### Structure

```
pages/login
pages/register
pages/dashboard
pages/company
pages/services
pages/budget-form
pages/budget-view

services/auth
services/budget
services/company
services/service-item
```
-------------------

###### TODOS
Company profile,
Handle NFS-e,
Mobile app,
Play Store Version,


