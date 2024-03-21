# Todo List Django Application

Welcome to the Todo List Django application repository! This application provides a simple platform for managing your tasks efficiently.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Task Management:** Add, edit, and delete tasks easily.
- **Task Status:** Mark tasks as completed or pending.
- **User Authentication:** Secure login system for managing tasks privately.
- **User-Specific Tasks:** Each user can have their own list of tasks.
- **Responsive Design:** Ensures compatibility across various devices.

## Installation

Follow these steps to set up the Todo List Django application:

### Using Docker

Follow these steps to set up the Todo List Django application with Docker:

1. **Clone the repository:**
   ```
   git clone https://github.com/Malickkk/Todo_List_Django.git
   ```

2. **Navigate to the project directory:**
   ```
   cd Todo_List_Django
   ```

3. **Run the application with Docker:**
   ```
   docker-compose up --build -d
   ```

4. **Access the application:**
   Once the containers are up and running, you can access the Todo List application by opening your web browser and navigating to `http://localhost:8000`.

### Without Docker

1. **Clone the repository:**
   ```
   git clone https://github.com/Malickkk/Todo_List_Django.git
   ```

2. **Navigate to the project directory:**
   ```
   cd Todo_List_Django
   ```

3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```
   python manage.py migrate
   ```

5. **Create a superuser (for accessing the admin panel):**
   ```
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```
   python manage.py runserver
   ```

## Usage

Once the server is running, you can access the Todo List application in your web browser by navigating to `http://localhost:8000`. You'll be prompted to log in or sign up to start managing your tasks.

Additionally, as a superuser, you can access the Django admin panel by navigating to `http://localhost:8000/admin`. This allows you to manage users and tasks directly from the admin interface.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or feature requests, please open an issue on GitHub or submit a pull request.

## License

---
