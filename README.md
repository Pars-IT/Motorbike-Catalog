Motorbike Catalog
==========

A web application built with Symfony 2 for managing and browsing motorbikes.
The project demonstrates a classic MVC architecture with CRUD operations, pagination, sorting, and file uploads.

## Features

* Motorbike management (CRUD)
* Pagination for listing items
* Sorting by different fields (id, price, etc.)
* Image upload for motorbikes
* Basic user management
* Server-side rendering with Twig templates

## Tech Stack

* PHP (Symfony 2.7)
* Doctrine ORM
* MySQL
* Twig Templating Engine

## Database Structure

* `motorbikes` – Stores bike information (model, engine, price, etc.)
* `user` – Basic user data

## Key Implementation Details

* Pagination implemented using Doctrine Paginator
* Dynamic sorting via query parameters
* File upload handling for product images
* MVC pattern using Symfony controllers, entities, and forms

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd motorbike-catalog
   ```

2. Install dependencies:

   ```
   composer install
   ```

3. Configure database:
   Update `app/config/parameters.yml`

4. Import database:

   ```
   mysql -u root -p < database.sql
   ```

5. Run application:

   ```
   php app/console server:run
   ```

6. Open in browser:

   ```
   http://localhost:8000
   ```

## Notes

This project was developed as an early practice project using Symfony 2 and demonstrates fundamental concepts such as CRUD operations, pagination, and MVC architecture.

## Author

Mohamad Habibi
