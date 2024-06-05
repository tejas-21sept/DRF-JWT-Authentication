# Django JWT Authentication with DRF

This project demonstrates how to implement JWT (JSON Web Token) authentication in a Django REST Framework (DRF) application. It includes custom user registration, login, password reset functionalities, and phone number validation without third-party packages.

## Features

- Custom User Model with Email and Phone Number
- JWT Authentication
- User Registration with Email and Phone Number
- User Login
- Password Change
- Password Reset via Email
- Phone Number Validation (Globally)

## Setup and Installation

### Prerequisites

- Python 3.x
- Django 4.x or 5.x
- Django REST Framework
- SimpleJWT
- django-dotenv

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/tejas-21sept/DRF-JWT-Authentication.git
   cd DRF-JWT-Authentication
   ```

2. **Create a virtual environment and activate it**:

   i.Open a terminal:

   - Windows: Open `Command Prompt` or `PowerShell`.
   - macOS/Linux: Open a terminal window.

   ii. Navigate to the project directory:

   ```python
     cd social_network_backend

   ```

   iii. Create the virtual environment:

   ```python
     python -m venv venv

   ```

   iv. Activate the virtual environment:

   ```python

     source venv/bin/activate  # Linux/macOS

     venv\Scripts\activate.bat  # Windows

   ```

3. **Install dependencies**:

```pip
  pip install -r requirements.txt
```

4. **Run the migrations**:

   ```python
       python manage.py makemigrations
       python manage.py migrate
   ```

5. **Create a .env file:**:
   Create a .env file in the root directory of your project and copy the contents of .env.example into it.

6. **Start the development server**:
   ```python
       python manage.py runserver
   ```
