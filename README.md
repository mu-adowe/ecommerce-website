# Rustys

## Overview
Rustys is a full-stack PHP project designed as an e-commerce platform for selling goods.

## Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher

### Steps
1. Clone the repository: `git clone https://github.com/yourusername/rustys.git`
2. Navigate to the project directory: `cd rustys`
3. Install PHP dependencies: `composer install`
4. Install JavaScript dependencies: `npm install`
5. Copy `.env.example` to `.env` and update environment variables: `cp .env.example .env`
6. Generate an app encryption key: `php artisan key:generate`
7. Run the database migrations: `php artisan migrate`
8. Start the local development server: `php artisan serve`
