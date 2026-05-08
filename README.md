# Inventory Management System

## Overview

The **Inventory Management System** is a Python-based command-line application developed using **Object-Oriented Programming (OOP)** principles.
This project is designed to manage different categories of products such as Electronics, Clothes, and Food items efficiently.

The system provides functionalities for adding, updating, removing, searching, and monitoring inventory stock through a simple and user-friendly interface.

---

# Key Features

* Add New Products
* Remove Existing Products
* Search Products by Name
* Update Product Quantity and Price
* Calculate Total Inventory Value
* Detect Low Stock Products
* Category-Based Product Management
* Interactive Command-Line Interface (CLI)

---

# Technologies Used

* Python 3
* Object-Oriented Programming (OOP)
* Abstract Classes (`ABC`)
* Command Line Interface (CLI)

---

# OOP Concepts Implemented

## 1. Abstraction

The `Product` class is implemented as an Abstract Base Class using Python's `ABC` module.

## 2. Inheritance

The following classes inherit from the `Product` class:

* Electronics
* Clothes
* Food

## 3. Polymorphism

Each product category overrides the `product_info()` method according to its own requirements.

## 4. Encapsulation

All product-related data is stored inside objects using constructors and class attributes.

---

# Project Structure

```bash id="i2c6u7"
Inventory-Management-System/
│
├── product.py       # Product and Category Classes
├── inventory.py     # Inventory Operations
├── main.py          # Main Execution File
└── README.md
```

---

# Product Categories

## Electronics

* Product Name
* Price
* Quantity
* Warranty

## Clothes

* Product Name
* Price
* Quantity
* Size

## Food

* Product Name
* Price
* Quantity
* Manufacturing Date
* Expiry Date

---

# System Functionalities

| Function       | Description                         |
| -------------- | ----------------------------------- |
| Add Product    | Adds a new product to inventory     |
| Remove Product | Deletes a product from inventory    |
| Search Product | Finds a product by name             |
| Update Product | Updates quantity and price          |
| Total Value    | Calculates total inventory worth    |
| Low Stock      | Displays products with low quantity |

---

# How to Run the Project

## Step 1: Clone Repository

```bash id="w0k2d1"
git clone <repository-link>
```

## Step 2: Open Project Folder

```bash id="gl1s8q"
cd Inventory-Management-System
```

## Step 3: Run the Program

```bash id="g7d2v5"
python main.py
```

---

# Sample Menu

```text id="u9a5o2"
===== Inventory Management System =====

1. Add Product
2. Remove Product
3. Search Product
4. Update Product
5. Get Total Value
6. Get Low Stock
7. Exit
```

---

# Future Improvements

The following features can be added in future versions:

* Graphical User Interface (GUI)
* Database Integration (MySQL / SQLite)
* Authentication System
* Sales & Billing Module
* Product Reports
* Barcode Scanner
* REST API Integration
* Web-Based Dashboard using FastAPI & React

---

# Learning Outcomes

This project helped in understanding:

* Python OOP Concepts
* Abstract Classes
* Inheritance & Polymorphism
* Data Management
* Modular Programming
* CLI Application Development

---

# Author

## Mohsin Saleem

BS Software Engineering

Python Developer | Software Engineering Student
