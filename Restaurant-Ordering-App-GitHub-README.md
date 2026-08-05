# Ember & Olive Restaurant Ordering App

A full-stack restaurant ordering application built with React Native
(Expo), Flask, and MySQL.

The application allows users to browse restaurant menus, search and
filter dishes, manage a basket, create an account, place orders, and
view order history through a mobile-friendly interface connected to a
Flask REST API backend.

## Technologies

**Frontend** - React Native - Expo - JavaScript

**Backend** - Python - Flask - REST API

**Database** - MySQL

**Tools** - Git/GitHub - XAMPP - phpMyAdmin

## Features

### User Features

-   Browse restaurant menu
-   Search and filter menu items
-   View categories and dishes
-   Add and remove items from basket
-   User registration and login
-   Submit delivery information
-   Place orders
-   View order history and status

### Backend Features

-   REST API communication
-   MySQL database integration
-   User authentication
-   Order processing
-   Server-side validation of prices and availability

## Project Structure

    Restaurant-Ordering-App
    ├── ProjektiRN/                  Frontend (React Native / Expo)
    ├── ProjektiRN/flask/            Backend (Flask API)
    └── ProjektiRN/database_setup.sql Database setup

## Screenshots

Add screenshots of the application here.

## Running the Project

### Database Setup

1.  Start Apache and MySQL using XAMPP.
2.  Open phpMyAdmin.
3.  Import:

```{=html}
<!-- -->
```
    ProjektiRN/database_setup.sql

This creates the required database, tables, and sample restaurant data.

### Backend Setup

Open a terminal in:

    ProjektiRN/flask

Create a virtual environment:

    python -m venv .venv

Activate it:

    .\.venv\Scripts\Activate.ps1

Install dependencies:

    pip install -r requirements.txt

Run Flask:

    python app.py

### Frontend Setup

Open another terminal in:

    ProjektiRN

Install dependencies:

    npm install

Start Expo:

    npx expo start

## Application Flow

1.  User browses the restaurant menu.
2.  Items are added to the basket.
3.  User creates an account or logs in.
4.  User places an order.
5.  Flask processes the request and communicates with MySQL.
6.  User can view previous orders.

## Notes

This project was developed to practice full-stack application
development, including mobile development, backend API creation,
database design, and frontend-backend communication.
