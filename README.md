# Ecommerce-Laravel

This is a Laravel-based e-commerce application. It provides features for managing products, categories, orders, users, and more.

## Features
- Product and category management
- Shopping cart and checkout
- Order management
- User authentication
- Admin dashboard
- Responsive frontend and backend

## Requirements
- PHP >= 7.3
- Composer
- MySQL or compatible database
- Node.js and npm (for frontend assets)

## Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/ayiTech1/Unishop-Ecommerce.git
   ```
2. Install dependencies:
   ```sh
   composer install
   npm install
   ```
3. Copy `.env.example` to `.env` and set your environment variables:
   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
4. Run migrations and seeders:
   ```sh
   php artisan migrate --seed
   ```
5. Start the development server:
   ```sh
   php artisan serve
   ```

## License
This project is open-source and available under the [MIT license](LICENSE).
