# DLS Internet Services REST API in Laravel

Welcome to the DLS Internet Services REST API project! This API provides endpoints for managing internet services for DLS customers. It's built using the Laravel framework.

## Features

- Create, read, update, and delete customer internet service records.
- Authenticate and secure API endpoints.
- Retrieve customer usage statistics and account information.
- Manage service plans and billing details.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)

## Getting Started

### Prerequisites

To run this project, you'll need the following:

- [Laravel](https://laravel.com/docs) installed.
- A compatible web server (e.g., Apache, Nginx).
- PHP and Composer installed.
- A database server (e.g., MySQL, PostgreSQL).

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/SFD153/DLS-Internet-Services-REST-API-PHP.git
   cd DLS-Internet-Services-REST-API-PHP

2. Install dependencies:

    ```sh
    composer install

3. Configure your .env file:

    ```sh
    cp .env.example .env
    php artisan key:generate

4. Run migrations and seeders:
    ```sh
    php artisan migrate --seed

5. Start the development server:
    ```sh
    php artisan serve

## Contributing
Contributions are welcome! If you encounter any bugs or have ideas for improvements, feel free to open an issue or submit a pull request.
