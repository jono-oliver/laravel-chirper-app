# Laravel Chirper App

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

A Twitter-like social media application built with Laravel, where users can create, edit, and delete short messages called "chirps".

## About This Project

This Laravel Chirper application was built as a learning experience following a course by **Josh Cirre**. It demonstrates core Laravel concepts including authentication, CRUD operations, database relationships, and modern web development practices.

## Features

- **User Authentication**: Register, login, and logout functionality
- **Chirp Management**: Create, read, update, and delete chirps (short messages)
- **User Relationships**: Chirps are associated with users
- **Responsive Design**: Modern, mobile-friendly interface
- **Authorization**: Users can only edit/delete their own chirps

## Technology Stack

- **Backend**: Laravel 12.x
- **Frontend**: Blade templates with Tailwind CSS
- **Database**: SQLite (development)
- **PHP**: 8.2+
- **Testing**: Pest PHP
- **Build Tools**: Vite

## Key Laravel Features Demonstrated

- **Eloquent ORM**: User-Chirp relationships
- **Authentication**: Built-in Laravel auth system
- **Migrations**: Database schema management
- **Controllers**: RESTful resource handling
- **Policies**: Authorization logic
- **Blade Components**: Reusable UI components
- **Middleware**: Route protection
- **Validation**: Form input validation

## Installation

1. Clone the repository
2. Install dependencies: `composer install`
3. Install Node.js dependencies: `npm install`
4. Copy environment file: `cp .env.example .env`
5. Generate application key: `php artisan key:generate`
6. Run migrations: `php artisan migrate`
7. Start the development server: `php artisan serve`
8. Build assets: `npm run dev`

## Development

This project includes several development tools:

- **Laravel Sail**: Docker-based development environment
- **Laravel Pint**: Code formatting
- **Pest**: Testing framework
- **Laravel Pail**: Log viewing

## Learning Resources

This project was created following educational content by Josh Cirre. For more Laravel learning resources:

- [Laravel Documentation](https://laravel.com/docs)
- [Laravel Bootcamp](https://bootcamp.laravel.com)
- [Laracasts](https://laracasts.com)

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
