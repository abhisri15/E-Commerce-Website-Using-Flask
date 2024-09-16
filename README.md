# E-Commerce Website using Flask

This project is a simple e-commerce website built using the Flask web framework. The application allows users to browse items, register and login, add products, and manage their transactions.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Introduction

The **E-Commerce Website** project demonstrates the use of the Flask framework to create a basic web application with an authentication system. The app manages users and products in a local SQLite database. Users can create accounts, log in, add items for sale, and browse available products.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Features

- User Registration & Login system
- Item listing with basic details like name, price, barcode, and description
- Add and manage products (admin functionality)
- SQLite for database management
- Flask templates for rendering HTML pages
- Responsive design with basic CSS

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Technologies Used

- **Python** (Flask, SQLAlchemy)
- **HTML/CSS** (Bootstrap)
- **SQLite** (Database management)
- **Jinja2** (Template engine for Flask)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Installation and Setup

To run this project locally, follow the steps below:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/username/ecommerce-flask.git
   cd ecommerce-flask
   ```
   
2. **Set up a virtual environment (optional but recommended)**:

  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  ```

3. **Install required packages**:

  ```bash
  pip install -r requirements.txt
  ```

4. **Set environment variables (on PowerShell/Terminal)**:

  ```bash
  set FLASK_APP=market.py
  set FLASK_ENV=development
  ```

5. **Create the SQLite database**:

  ```bash
  flask shell
  >>> from market import db
  >>> db.create_all()
  ```

6. **Run the Flask application**:

  ```bash
  flask run
  ```

7. **Access the application**:

  Open your browser and go to http://127.0.0.1:5000/

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Usage

- **Homepage**: Displays the homepage with links to browse available products or login.
- **Market Page**: Lists all the available products with an option to add products (if logged in).
- **User Authentication**: New users can sign up, and existing users can log in to manage their profiles.
- **Database Management**: Product details and user accounts are stored in a local SQLite database.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Contributing

Contributions to this project are welcome! If you find any bugs or have any improvements in mind, feel free to create an issue or submit a pull request.

1. **Fork the repository**
2. **Create your feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)
