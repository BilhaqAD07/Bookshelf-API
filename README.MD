# Bookshelf API

## Overview
The Bookshelf API is a backend service for managing a collection of books. It allows users to perform CRUD (Create, Read, Update, Delete) operations on books.

## Features
- Add a new book
- Retrieve all books
- Retrieve a single book by ID
- Update book details
- Delete a book

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/BilhaqAD07/Bookshelf-API.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Bookshelf-API
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

## Usage
1. Start the server:
    ```sh
    npm start
    ```
2. The API will be available at `http://localhost:9000`.

## Endpoints
- `GET /books` - Retrieve all books
- `GET /books/:id` - Retrieve a book by ID
- `POST /books` - Add a new book
- `PUT /books/:id` - Update a book by ID
- `DELETE /books/:id` - Delete a book by ID

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.