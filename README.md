# Restaurant Management System

A RESTful backend application built with FastAPI, Tortoise ORM, and PostgreSQL to manage restaurants, menus, users, authentication, and food ordering. The system supports role-based access control, order management, restaurant analytics, and menu search and filtering.

## Tech Stack

- Backend: FastAPI
- ORM: Tortoise ORM
- Database: PostgreSQL
- Database Migrations: Aerich
- Authentication: JWT-based authentication
- Testing: Pytest
- API Documentation: Swagger UI / OpenAPI

## User Roles

1. Normal User

- Register and manage their account.
- Log in and log out
- View restaurants and their menus.
- Search and filter restaurants and menu items.
- Place orders containing multiple items from the same restaurant.
- View their order history.

2. Restaurant Owner

- Manage menu items for their assigned restaurant.
- Add new items to the restaurant menu.
- Update item prices and available quantities.
- Remove items from the menu.
- View restaurant analytics and order statistics.
- View orders placed at their restaurant.
- Identify top customers based on order count.

3. Admin

- Create restaurants and assign restaurant owners.
- Manage restaurant creation and ownership assignments.
