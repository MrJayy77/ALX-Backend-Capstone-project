🛒 Ecommerce API

A robust and scalable RESTful API built with Django and Django REST Framework (DRF) for managing products, users, orders, payments, and authentication. This project demonstrates best practices for building and deploying backend APIs.

🚀 Features

User Authentication – Registration, login, logout, JWT authentication

Product Management – CRUD operations for products and categories

Order Management – Create and track customer orders

Cart System – Add, update, and remove items from cart

Admin Dashboard – Manage users, orders, and inventory

API Documentation – Auto-generated with DRF and drf-yasg

Scalable Structure – Modular and ready for production deployment


🧩 API Endpoints (Examples)
Endpoint	Method	Description
/api/auth/register/	POST	Register a new user
/api/auth/login/	POST	Log in and receive JWT
/api/products/	GET	List all products
/api/products/{id}/	GET	Retrieve single product
/api/cart/	GET, POST	View or add to cart
/api/orders/	GET, POST	View or create orders

🧰 Technologies Used

Python 3.10+

Django 5.x

Django REST Framework

SQLite / PostgreSQL

SimpleJWT for authentication

🌐 Deployment (Production)

To deploy:

Set up your environment variables in .env

Configure a production-ready database (e.g., PostgreSQL)

Use Gunicorn and Nginx (or Render, Railway, or Heroku)

Run:

python manage.py collectstatic
gunicorn ecommerce.wsgi

🧑‍💻 Developer

Author: Abraham Kwesi James
Institution: Klintaps University College
Project: Django Ecommerce API
Contact: abrahamkwesijames@gmail.com

📜 License

This project is open-source under the MIT License.