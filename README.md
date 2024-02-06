# Expense Tracker Documentation

## Overview
The Expense Tracker application is designed to help users manage their expenses by providing features such as user registration, login/logout functionality, expense addition, expense listing, and category-wise expense summation. The application is implemented in Java and utilizes object serialization to persist user and expense data.

## Classes

### `Expense` Class
- Represents an expense with attributes: date, category, and amount.
- Provides a constructor to initialize expense details.
- Contains getter methods for accessing expense attributes.

### `User` Class
- Represents a user with attributes: username, password, and a list of expenses.
- Provides a constructor to create a new user with a username and password.
- Includes methods to retrieve username, password, and the list of expenses.
- Allows adding expenses to the user's list.

### `ExpenseTracker` Class
- Manages user registration, login/logout, expense addition, and data persistence.
- Uses object serialization to save and load user data.
- Provides methods for listing expenses, displaying category-wise summation, and accessing the current user.

### `ExpenseTrackerApp` Class
- The main class that serves as the entry point for the Expense Tracker application.
- Implements a console-based user interface to interact with the Expense Tracker functionalities.

## Features

### 1. User Registration
- Users can register by providing a username and password.
- User data is stored and loaded using object serialization.

### 2. User Login/Logout
- Users can log in with their username and password.
- A logged-in user can add expenses, list expenses, and view category-wise summation.
- The application supports user logout.

### 3. Expense Management
- Users can add expenses with details such as date, category, and amount.
- Expenses are associated with the currently logged-in user.
- Expense data is saved and loaded from a file (`expense_data.txt`) using object serialization.

### 4. Expense Listing
- Users can list their expenses based on different sorting options: unsorted, sorted by date, or sorted by category.

### 5. Category-wise Summation
- Users can view the total expenses for each expense category.

### 6. Console User Interface
- The application provides a simple console-based menu for user interaction.
- Users can navigate through different options using numeric choices.

## Data Persistence
- User and expense data are persisted between application sessions using object serialization.
- Data is stored in a file (`expense_data.txt`) to ensure continuity across program executions.

## Error Handling
- The application handles exceptions related to file I/O and date parsing gracefully.
- Users receive informative messages for invalid inputs or operations.

## Future Improvements
- Enhance security by implementing password hashing.
- Add more advanced sorting and filtering options for expense listing.
- Implement a graphical user interface (GUI) for a more user-friendly experience.
- Allow users to delete or edit their expenses.

This documentation provides an overview of the design and features of the Expense Tracker application, offering a foundation for understanding its functionality and potential areas for improvement.
