# Bookshop Project

Welcome to my Bookshop project repository. This project is a simple bookshop management system developed using Java.

## Introduction

This project is a Bookshop management system that allows users to manage book information. It includes functionality for adding, updating, and deleting book records, as well as viewing the list of books.

## Features

- Add new book records
- Update existing book records
- Delete book records
- View all book records

## Technologies Used

- Java
- JDBC (Java Database Connectivity) for database interaction
- MySQL or any other relational database (you can specify your database)

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**

    ```bash
    git clone https://github.com/Hirdhyakk/BookShop.git
    ```

2. **Navigate to the project directory**

    ```bash
    cd BookShop
    ```

3. **Set up the database**

    - Create a MySQL database (or use any other database) and configure it in the project.
    - Run the SQL scripts provided in the `sql/` directory to set up the necessary tables.

4. **Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse, preferred is Netbeans)**

5. **Configure the database connection**

    - Update the database connection settings in the `config.properties` file or directly in the Java code where the connection is established.

6. **Compile and run the application**

    - Use your IDE's build tools to compile the project, or run the following command in the terminal:

    ```bash
    javac -d bin src/*.java
    java -cp bin com.yourpackage.Main
    ```

## Usage

Run the main class to start the bookshop management system. Follow the on-screen instructions to interact with the system. The command-line interface will guide you through the various options for managing books.

