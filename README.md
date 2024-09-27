<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/abdulrahmanRadan/filament-tutorial/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Filament Tutorial

This project is a tutorial using the Laravel framework with Filament. It is designed to facilitate the rapid and efficient development of admin interfaces. Filament provides powerful tools for building beautiful, user-friendly interfaces.

### Key Features

- **User-Friendly Interface**: Filament offers a flexible and attractive user interface.
- **Data Models**: Strong support for creating and managing data models.
- **Powerful Tools**: A wide range of tools for building a custom dashboard.
- **Full Customization**: Extensive options for customizing the project to fit your needs.

## How to Download and Set Up the Project

To download and set up the `filament-tutorial` project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/abdulrahmanRadan/filament-tutorial.git
   ```

2. Navigate to the project directory:
   ```bash
   cd filament-tutorial
   ```

3. Install the dependencies using Composer:
   ```bash
   composer install
   ```

4. Create a `.env` file by copying the example:
   ```bash
   cp .env.example .env
   ```

5. Generate the application key:
   ```bash
   php artisan key:generate
   ```

6. Set up your database credentials in the `.env` file.

7. Run the migrations to create the necessary tables:
   ```bash
   php artisan migrate
   ```

8. (Optional) Seed the database:
   ```bash
   php artisan db:seed
   ```

9. Run the development server:
   ```bash
   php artisan serve
   ```

Now, you can access the application at `http://localhost:8000`.

## Learning Filament

You can check out the [official Filament documentation](https://filamentphp.com/docs) to learn how to use it effectively. The site offers comprehensive resources to get you started with Filament quickly.

## Contributors

We would like to thank the contributors who have supported the development of the Filament Tutorial project. If you are interested in contributing, you can visit the [Contributing Guide](https://github.com/abdulrahmanRadan/filament-tutorial#contributing).

## Code of Conduct

To ensure that the Filament community is welcoming to everyone, please review and adhere to the [Code of Conduct](https://github.com/abdulrahmanRadan/filament-tutorial#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within the project, please send an email to [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
