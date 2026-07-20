# Sofra Website 🍽️

Welcome to **Sofra**, a premium recipe sharing and discovery web application built with Django. Sofra provides a beautiful interface for food enthusiasts to explore, manage, rate, and save their favorite recipes.

## ✨ Features

- **Premium Modern UI**: A visually stunning design built with Vanilla HTML/CSS/JS, focusing on beautiful typography, subtle animations, and a polished user experience.
- **User Authentication**: Secure sign-up, login, and personalized user profiles with custom avatars.
- **Recipe Management**: Full CRUD functionality. Users can create, read, edit, and delete their own recipes.
- **Discover & Search**: Easily find what you are craving by searching recipes by name or ingredients.
- **Ratings & Favorites**: Rate recipes out of 5 stars and add them to your personal favorites list for quick access later.
- **Admin Dashboard**: Dedicated staff dashboard for easy recipe management and moderation.

## 🛠️ Technology Stack

- **Backend Framework**: Django (Python)
- **Frontend**: HTML5, Vanilla CSS, JavaScript
- **Database**: SQLite (Development)
- **Media Storage**: Django File System (Local/Media Root)

## 🚀 Getting Started

### Prerequisites

Make sure you have [Python](https://www.python.org/) installed on your machine.

### Local Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd Sofra/Recipes/mysite
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser** (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

7. **Access the application**:
   Open your browser and navigate to `http://127.0.0.1:8000/`.

## 📁 Project Structure

```text
mysite/
│
├── mysite/           # Django core settings and routing
├── users/            # User authentication and profile management
├── recipes/          # Core app handling recipe models, views, favorites, and ratings
├── templates/        # HTML templates for the frontend
├── static/           # CSS, JavaScript, and static images
├── media/            # User-uploaded content (recipe images, avatars)
├── requirements.txt  # Project dependencies
└── manage.py         # Django management script
```
