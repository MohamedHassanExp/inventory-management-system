# Django Inventory Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)](https://www.djangoproject.com/)

A full-stack, web-based inventory management application built with Django that allows users to track items, manage warehouses, and monitor stock levels through a secure, authenticated dashboard.

##  Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)

##  About the Project

This project provides a solution for managing physical inventory. It features a complete user authentication system (registration, login, password reset), a visual dashboard for tracking stock, and database models for categorizing items and routing them to specific warehouses. 

### Tech Stack
*   **Language:** Python 3.10+
*   **Framework:** Django
*   **Frontend:** HTML/CSS (Django Templates)
*   **Database:** SQLite (Default)

##  Getting Started

Follow these instructions to set up the Django project locally.

### Prerequisites

*   Python 3.10 or higher
*   Pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/MohamedHassanExp/inventory-management-system.git](https://github.com/MohamedHassanExp/inventory-management-system.git)
2. Navigate to the project directory
   ```bash
   cd inventory-management-system-main
3. Install dependencies
   ```bash
   pip install -r requirements.txt
4. Apply database migrations
   ```bash
   python manage.py migrate
5. Create a superuser for admin access (Optional)
   ```bash
   python manage.py createsuperuser

### Usage 

To start the local development server, run
```bash
python manage.py runserver
```
Open your web browser and navigate to http://127.0.0.1:8000/. From there, you can register a new account, log in, and begin adding items, categories, and warehouses to your inventory dashboard. To access the backend admin panel, navigate to http://127.0.0.1:8000/admin
