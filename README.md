# Flask Blog

A simple blog application built with Flask, SQLAlchemy, and other modern web development tools. This project allows users to register, log in, create posts, and reset their passwords.

## Features

- User registration and authentication
- Password reset functionality with secure tokens
- Post creation, editing, and deletion
- User profile management
- Responsive design with Bootstrap

## Getting Started

### Prerequisites

- Python 3.8+
- Virtualenv (recommended)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/flask-blog.git
    cd flask-blog
    ```

2. **Install the dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `.env` file** with the following environment variables:

    ```plaintext
    FLASK_APP=run.py
    FLASK_ENV=development
    SECRET_KEY=your_secret_key
    SQLALCHEMY_DATABASE_URI=sqlite:///site.db
    MAIL_SERVER=smtp.googlemail.com
    MAIL_PORT=587
    MAIL_USE_TLS=True
    MAIL_USERNAME=your_email@gmail.com
    MAIL_PASSWORD=your_password
    SECURITY_PASSWORD_SALT=your_security_salt
    ```

4. **Run the application**:

    ```bash
    flask run
    ```

5. **Access the application**:

    Open your web browser and go to `http://127.0.0.1:5000/`.

## Project Structure

```plaintext
flask-blog/
├── flaskblog/
│   ├── __init__.py
│   ├── config.py
│   ├── models.py
│   ├── templates/
│   ├── static/
│   ├── main/
│   ├── users/
│   ├── posts/
│   └── errors/
|   |
├── config.py
├── run.py
├── requirements.txt
└── README.md
