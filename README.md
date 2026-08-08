# Hotel Reservation System

A terminal-based **Hotel Reservation System** developed using **Java**. This project is designed to simulate the basic operations of a hotel booking system through a simple command-line interface.

The system allows users to view available rooms, make reservations, manage existing bookings, and perform other essential hotel-related operations. It was created as a practice project to strengthen concepts such as **Object-Oriented Programming (OOP), Exception Handling, Collections, JDBC, and MySQL database connectivity**.

## 🚀 Features

- View available hotel rooms
- Display room details and pricing
- Make a new room reservation
- Store and manage customer information
- View existing reservations
- Search for reservations
- Cancel existing reservations
- Handle invalid user input and exceptions
- Store reservation data using a MySQL database
- Interactive terminal-based menu
- JDBC integration for communication between Java and MySQL

## 🛠️ Technologies Used

- **Java** – Core programming language
- **OOP** – Classes, objects, inheritance, encapsulation, etc.
- **JDBC** – Database connectivity
- **MySQL** – Storage and management of reservation data
- **Exception Handling** – Handling invalid input and runtime errors
- **Collections Framework** – Managing data within the application
- **IntelliJ IDEA** – Development environment

## 📂 Project Structure

The project is organized into different classes based on their responsibilities. This helps keep the application modular and makes the code easier to understand and maintain.

Possible components include:

- `Main` – Entry point of the application
- `Hotel` – Handles hotel-related operations
- `Room` – Represents room information
- `Customer` – Stores customer details
- `Reservation` – Handles reservation information
- `Database` – Manages MySQL/JDBC connectivity
- `ReservationManager` – Handles booking and cancellation operations

## 🔄 How It Works

When the application starts, the user is presented with a terminal-based menu. The user can select an operation by entering the corresponding option.

For example:

```text
===== HOTEL RESERVATION SYSTEM =====

1. View Available Rooms
2. Make Reservation
3. View Reservations
4. Search Reservation
5. Cancel Reservation
6. Exit

Enter your choice:
