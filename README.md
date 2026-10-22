<div align="center">
  <img src="public/assets/images/logo_bengkod.svg" alt="BENGTIX logo" width="240">

  <h1>BENGTIX</h1>

  <p>A friendly and modern event ticketing platform built with Laravel.</p>

  <p>
    <a href="https://github.com/PVegananda/ticketing-laravel-12">
      <img src="https://img.shields.io/github/stars/PVegananda/ticketing-laravel-12?style=for-the-badge&logo=github" alt="GitHub stars">
    </a>
    <a href="https://github.com/PVegananda/ticketing-laravel-12/network/members">
      <img src="https://img.shields.io/github/forks/PVegananda/ticketing-laravel-12?style=for-the-badge&logo=github" alt="GitHub forks">
    </a>
    <a href="https://github.com/PVegananda/ticketing-laravel-12">
      <img src="https://img.shields.io/github/last-commit/PVegananda/ticketing-laravel-12?style=for-the-badge" alt="Last commit">
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/PHP-%5E8.2-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8.2">
    <img src="https://img.shields.io/badge/Laravel-12-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel 12">
    <img src="https://img.shields.io/badge/Tailwind%20CSS-3.1-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  </p>
</div>

## About BENGTIX

BENGTIX makes it simple to discover events and book tickets in one place. The
platform is designed to give event attendees a smooth experience while giving
administrators the tools they need to manage event categories and ticket data.

## Features

- Browse upcoming events and view event details.
- Explore ticket options and prices for each event.
- Create an account, sign in, and manage a profile.
- Manage event categories through the admin dashboard.
- Use role-aware authentication and email verification.
- Enjoy a responsive interface powered by Tailwind CSS and Vite.

## Tech Stack

- **Backend:** PHP 8.2+ and Laravel 12
- **Frontend:** Blade, Tailwind CSS, Alpine.js, and Vite
- **Database:** Any database supported by Laravel, including SQLite and MySQL
- **Testing:** Pest and PHPUnit

## Getting Started

### Prerequisites

Make sure the following tools are installed:

- PHP 8.2 or newer
- Composer
- Node.js and npm
- A database supported by Laravel

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/PVegananda/ticketing-laravel-12.git
   cd ticketing-laravel-12
   ```

2. Install PHP dependencies:

   ```bash
   composer install
   ```

3. Create a local `.env` file, configure the database connection, and generate
   an application key:

   ```bash
   touch .env
   php artisan key:generate
   ```

4. Configure the database connection in `.env`, then run the migrations and
   seed the sample data:

   ```bash
   php artisan migrate --seed
   ```

5. Install frontend dependencies and build the assets:

   ```bash
   npm install
   npm run build
   ```

6. Start the local development server:

   ```bash
   php artisan serve
   ```

   For a complete development workflow with the queue, logs, and Vite, use:

   ```bash
   composer run dev
   ```

Open [http://localhost:8000](http://localhost:8000) in your browser to visit
BENGTIX.

## Running Tests

Run the application test suite with:

```bash
composer test
```

## Contributing

Contributions are welcome! If you have an idea, find a bug, or want to improve
the project, please open an issue or submit a pull request. Before submitting,
make sure your changes are tested and follow the existing code style.

## Project Status

BENGTIX is an evolving project. Features and documentation will continue to
improve as the platform grows.
