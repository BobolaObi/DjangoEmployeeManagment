# Full Stack Web Application

A full-stack application built with Django for the backend, Vue.js for the frontend, and PostgreSQL for the database. Follow the tutorial [here](https://art-of-engineer.blogspot.com/2021/07/python-django-postgre-sql-vue-js-full.html) for more details.

## 🛠 Installation

### Prerequisites

- Python 3.8 or above
- PostgreSQL
- Node.js

### Setup

1. **Clone the Repository**
    ```bash
    git clone <repo_url>
    ```

2. **Create and Activate Virtual Environment**
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install Backend Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Install Frontend Dependencies**
    ```bash
    npm install
    ```

5. **Set Up Environment Variables**
    ```bash
    cp .env.example .env
    ```
    Fill in your database credentials in the `.env` file.

6. **Migrate the Database**
    ```bash
    python manage.py migrate
    ```

## 🚀 Usage

1. **Start the Django Backend**
    ```bash
    python manage.py runserver
    ```

2. **Start the Vue.js Frontend (in a new terminal)**
    ```bash
    npm run serve
    ```

Visit `http://127.0.0.1:8000` in your browser.

## 📖 Development

- **Backend**: Located in the `backend` directory. It includes models, views, and serializers.
- **Frontend**: Located in the `frontend` directory. Components are in `src/components`, and the main entry point is `src/main.js`.

## 👥 Contributing

Fork the repo, make your changes in a new branch, and create a pull request.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
# DjangoEmployeeManagment
