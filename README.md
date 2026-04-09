"# Library Management System

A Django-based web application for managing a library's book collection and categories.

## Features

- Add, view, update, and delete books
- Manage book categories
- Upload book and author photos
- Track book status (available, sold, rented)
- Set prices and rental information

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd libaray
   ```

2. Install Django:
   ```
   pip install django
   ```

3. Apply migrations:
   ```
   python manage.py migrate
   ```

4. Run the development server:
   ```
   python manage.py runserver
   ```

5. Open your browser and go to `http://127.0.0.1:8000/`

## Usage

- **Home Page**: View all books and categories, add new books and categories
- **Books Page**: Browse all books
- **Update**: Edit book details
- **Delete**: Remove books from the system

## Technologies Used

- Django 5.1.4
- Bootstrap (for styling)
- Chart.js (for potential charts)
- FontAwesome (for icons)

## Project Structure

- `libaray/`: Main Django project settings
- `main/`: Library management app
- `templates/`: HTML templates
- `static/`: CSS, JS, and image files
- `media/`: Uploaded photos

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source. Feel free to use and modify." 
