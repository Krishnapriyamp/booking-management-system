# Booking Management System

A web-based Booking Management System developed using Laravel and MySQL. The system provides separate user and admin dashboards for managing bookings, users, and webpage content.

## Features

- User registration and login
- User dashboard
- Admin dashboard
- Create, view, update, and delete bookings
- User management
- Webpage content management
- User profile management
- MySQL database integration
- Authentication and authorization

## Technologies Used

- Laravel
- PHP
- MySQL
- Blade
- HTML
- CSS
- JavaScript
- Bootstrap

## Project Structure

- `app/` – Application logic, controllers, and models
- `database/` – Database migrations and seeders
- `resources/views/` – Blade templates
- `routes/` – Application routes
- `public/` – Public assets
- `config/` – Application configuration

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/Krishnapriyamp/booking-management-system.git
```

### 2. Go to the Project Folder
```bash
cd booking-management-system/bookingms
```

### 3. Install PHP Dependencies
```bash
composer install
```

### 4. Create the Environment File
On Windows PowerShell:
```powershell
Copy-Item .env.example .env
```

### 5. Generate the Application Key
```bash
php artisan key:generate
```

### 6. Configure the Database
Create a MySQL database and update the following values in your `.env` file:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_bms
DB_USERNAME=root
DB_PASSWORD=
```

### 7. Run Database Migrations
```bash
php artisan migrate
```

### 8. Start the Laravel Server
```bash
php artisan serve
```

Open the application in your browser:
```text
http://127.0.0.1:8000
```

## Author

Krishna Priya MP

Computer Science and Engineering Graduate
