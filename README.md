# Blog Web Application

This project is a web application built using **Django**. It provides blogging functionality, allowing users to create, manage, and interact with posts dynamically.

## Features

- **User Authentication**: Secure login and registration system.
- **Post Management**: Create, edit, and delete blog posts.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Comments**: Users can add and manage comments on blog posts.
- **Search and Filter**: Search functionality to find posts by keywords and filters for categories.
- **Admin Panel**: Django's built-in admin panel for managing users and content.

## Requirements

- Python 3.10+
- Django 2024
- PostgreSQL (or any compatible database)
- Virtual Environment (recommended)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OmarsPrana/blog.git
   cd blog
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the database:**
   - Update `DATABASES` in `settings.py` with your database credentials.

5. **Run migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Create a superuser:**
   ```bash
   python manage.py createsuperuser
   ```

7. **Start the development server:**
   ```bash
   python manage.py runserver
   ```

## Usage

- Access the application at `http://127.0.0.1:8000/`.
- Log in as a superuser to manage posts and users.
- Explore the blog to create, edit, and interact with content.

## File Structure

- `blog/` - Main application folder containing views, models, and templates.
- `static/` - Static files such as CSS, JavaScript, and images.
- `templates/` - HTML templates for the blog pages.
- `manage.py` - Django's command-line utility for administrative tasks.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
