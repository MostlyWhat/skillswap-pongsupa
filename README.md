# skillswap-pongsupa

SkillSwap design and implementation for Rize's Software Development Course

## Prerequisite

Please make sure to have the following packages installed:

- PHP 8.5+
- Composer
- Node.js and npm
- PostgreSQL, MySQL, or SQLite

Note: You can use [php.new](https://php.new/) to install everything above except Node.js and npm.

## Installation

1. Install the packages above.
2. Clone the repository and cd to cloned project directory.
3. Install dependencies:

    ```bash
   composer install
   npm install
   ```

4. Setup environmental variables:

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. Configure your database connection in `.env`, then run migrations:

   ```bash
   php artisan migrate
   ```

6. Start the development server:

   ```bash
   composer run dev
   ```

## Tech Stack

- Laravel - Backend Framework
- Svelte 5 - Frontend Framework
- TailwindCSS - Styling
- PostgreSQL - Database
