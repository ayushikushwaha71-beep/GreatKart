# GreatKart - Django E-Commerce Platform

GreatKart is a full-stack e-commerce web application developed using Django. The platform provides a complete online shopping experience with user authentication, product management, category organization, shopping cart functionality, and a responsive user interface.

The project demonstrates Django backend development, database management, template integration, and implementation of core e-commerce workflows.

---

## Features

### User Management

- User registration and authentication
- Secure login and logout functionality
- User profile management
- User dashboard

### Product Management

- Product listing and product detail pages
- Category-based product organization
- Product image management
- Dynamic product display
- Admin-based product management

### Shopping Cart

- Add products to cart
- Update cart items
- Remove products from cart
- Order management workflow

### Administration

- Django admin panel integration
- Manage products and categories
- Manage users and orders

---

## Technology Stack

### Backend

- Python
- Django
- Django ORM

### Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

### Database

- SQLite (Development)

### Tools

- Git
- GitHub
- Visual Studio Code

---

## Project Structure

```
GreatKart/
│
├── accounts/          # Authentication and user management
├── category/          # Product categories
├── store/             # Product and store functionality
├── carts/             # Shopping cart management
├── orders/            # Order processing
├── templates/         # HTML templates
├── static/            # Static assets
├── media/             # Uploaded product images
├── manage.py
└── requirements.txt
```

---

## Installation and Setup

### Clone Repository

```bash
git clone https://github.com/ayushikushwaha71-beep/GreatKart.git
```

### Navigate to Project Directory

```bash
cd GreatKart
```

### Create Virtual Environment

```bash
python -m venv env
```

### Activate Virtual Environment

Windows:

```bash
env\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Database Migrations

```bash
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Application will be available at:

```
http://127.0.0.1:8000/
```

---


## Future Enhancements

- Payment gateway integration
- Product reviews and ratings
- Wishlist functionality
- Advanced search and filtering
- REST API integration
- Cloud deployment

---

## Author

**Ayushi Kushwaha**
