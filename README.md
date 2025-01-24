# Laravel Project Setup

## Requirements
- PHP 8.0 or higher
- Composer
- Node.js and npm
- MySQL or compatible database

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Install JavaScript dependencies:
   ```bash
   npm install
   npm run dev
   ```

4. Create a copy of the `.env` file:
   ```bash
   cp .env.example .env
   ```

5. Generate the application key:
   ```bash
   php artisan key:generate
   ```

6. Set up the database:
   - Update `.env` with your database credentials.
   - Run migrations:
     ```bash
     php artisan migrate
     ```

7. Run the application:
   ```bash
   php artisan serve
   ```

## Additional Commands
- To compile assets for production:
  ```bash
  npm run build
  ```
