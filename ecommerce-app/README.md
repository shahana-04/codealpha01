# E-commerce Store

A simple e-commerce application built with Django.

## Features

- Product listings
- Product details
- Shopping cart
- User registration and login
- Order processing
- Order history

## Setup

1. Clone the repository.
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment: `venv\Scripts\Activate.ps1` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Navigate to the ecommerce directory: `cd ecommerce`
6. Run migrations: `python manage.py migrate`
7. Create a superuser: `python manage.py createsuperuser`
8. Run the server: `python manage.py runserver`

## Usage

- Visit http://127.0.0.1:8000/ to view the site.
- Register a new user or login.
- Browse products, add to cart, checkout.
- View order history.

## Database

Uses SQLite by default. Products can be added via the admin panel at /admin/