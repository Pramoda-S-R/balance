# Hakogane - Anime Expense Tracker

**Hakogane** is a sleek, anime-themed personal expense tracker designed to help you manage your monthly finances with style. It features a unique 8th-of-the-month cycle system, salary tracking, and a sharp, industrial "Protocol" aesthetic.

## 🛠️ Tech Stack

This project is built using a modern Python stack:

*   **Backend Framework**: [Flask](https://flask.palletsprojects.com/) (Python) - Lightweight and flexible.
*   **Database ORM**: [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) - For easy database interactions.
*   **Authentication**: [Flask-Login](https://flask-login.readthedocs.io/) - Secure user session management.
*   **Database**:
    *   **Development**: [SQLite](https://www.sqlite.org/index.html) (`balance.db`) - Local, file-based database for easy setup.
    *   **Production**: [PostgreSQL](https://www.postgresql.org/) (Recommended for Vercel) - Robust and scalable.
*   **Dependency Management**: [uv](https://github.com/astral-sh/uv) - Extremely fast Python package installer and resolver.
*   **Deployment**: [Vercel](https://vercel.com/) - Serverless deployment configuration included.

## ✨ Key Features

1.  **Anime UI Aesthetic**: Dark mode with cyan accents, glassmorphism cards, and custom artwork backgrounds.
2.  **Monthly Cycle Logic**: Automatically tracks finances from the **8th of the current month** to the **7th of the next month**.
3.  **Salary / Credit Tracking**: Input your monthly allowance or salary to see your remaining balance in real-time.
4.  **Transaction Logging**: Record every expense with date, time, and description.
5.  **Multi-User Support**: Secure registration and login for multiple users.

## 🚀 Quick Start

1.  **Install `uv`** (if not already installed):
    ```bash
    pip install uv
    ```

2.  **Run the Application**:
    ```bash
    uv run app.py
    ```

3.  **Access the Dashboard**:
    Open your browser and navigate to `http://127.0.0.1:5000`.

## 📂 Project Structure

*   `app.py`: Main application logic and routing.
*   `models.py`: Database schema definitions (User, Transaction, MonthlyBudget).
*   `templates/`: HTML files for the UI (Login, Register, Dashboard).
*   `static/`: CSS styles and image assets.
*   `vercel.json`: Configuration for deploying to Vercel.

---

