# Library Management System

This Flask-based Library Management System allows users to manage a collection of books, including adding, editing, and deleting book entries. The system uses SQLAlchemy with SQLite for database operations and provides a simple and effective user interface for interacting with book data.

## OUTPUT


## Project Structure

Here's a breakdown of the project files and their purpose:

- **`main.py`**: Contains the Flask application setup, routes, database configuration, and CRUD operations.
- **`index.html`**: Displays the list of all books and links for editing and deleting each book.
- **`add.html`**: Provides a form to add a new book to the database.
- **`edit_rating.html`**: Allows the user to update the rating of an existing book.

## Features

- **List Books**: View all books stored in the database.
- **Add Book**: Add a new book with details such as title, author, and rating.
- **Edit Book**: Update the rating of an existing book.
- **Delete Book**: Remove a book entry from the database.

## Installation

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- Python installed on your system.
- pip for managing Python packages.

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/sarvesh-2109/Library-Management-System.git
cd Library-Management-System
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Start the Application

Run the Flask application:

```bash
python main.py
```

Navigate to `http://127.0.0.1:5000/` in your web browser to interact with the application.

## Usage

- **Homepage**: Displays all the books and provides options to add, edit, or delete a book.
- **Add a Book**: Navigate to the "Add New Book" link, fill in the form, and submit it to add a book.
- **Edit a Book**: Click the "Edit Rating" link next to any book to update its rating.
- **Delete a Book**: Click the "Delete" link next to any book to remove it from the library.

## Contributing

Contributions to the project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

