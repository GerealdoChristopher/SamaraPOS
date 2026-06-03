# SamaraPOS

A modern Point of Sale (POS) system built with Laravel for small businesses.

## ✨ Features

- 🔐 User login with roles (Admin / Cashier)
- 📦 Product and category management
- 🛒 POS screen with cart and checkout
- 🧾 Printable invoices
- 📊 Sales reports
- 📉 Stock control

## 🛠️ Tech Stack

- **Framework:** Laravel
- **Frontend:** Blade + Tailwind CSS
- **Database:** MySQL / SQLite

## 🚀 Installation

```bash
# Clone repository
git clone https://github.com/GerealdoChristopher/SamaraPOS.git

# Enter directory
cd SamaraPOS

# Copy environment file
cp .env.example .env

# Install PHP dependencies
composer install

# Install NPM dependencies
npm install

# Generate app key
php artisan key:generate

# Run migrations and seeders
php artisan migrate --seed

# Start development server
php artisan serve
