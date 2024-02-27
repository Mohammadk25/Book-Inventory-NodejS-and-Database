# Book Inventory System

The Book Inventory System is a web-based application designed to manage a collection of books. It provides functionalities for storing book details, categorizing books, and viewing them in a user-friendly interface. The system is built using Node.js for the backend, Express.js for routing, Sequelize as the ORM for interacting with the database, and a MySQL database to store book and category information.

## Features

1. **Book Management:**
   - Add new books to the inventory.
   - View existing books with details such as title, author, and category.

2. **Category Management:**
   - Create and manage categories to organize books.

3. **User-Friendly Interface:**
   - Intuitive frontend interface for easy navigation and interaction.
   - Ability to view and add books using a web browser.

4. **Database Integration:**
   - Utilizes MySQL database to store book and category information.
   - Implements Sequelize ORM for efficient database operations.

5. **Scalable and Customizable:**
   - Easily extendable to add new features or modify existing ones.
   - Scalable architecture to handle a growing collection of books.

## Setup

### Installation:

1. Clone the repository and install dependencies using `npm install`.

### Database Setup:

1. Create a MySQL database named `book_inventory`.
2. Run provided SQL scripts to create tables for books and categories.

### Server Setup:

1. Initialize the server using `node server.js`.

### Frontend:

1. Open `index.html` in a web browser to access the frontend interface.

## Usage

### View Books:

- Browse through the list of available books.
- Filter books by category or search for specific titles.

### Add Books:

- Enter book details such as title, author, and category to add new books.

### Manage Categories:

- Create, edit, or delete categories to organize books effectively.

### Database Management:

- Perform CRUD operations on books and categories via API endpoints.
