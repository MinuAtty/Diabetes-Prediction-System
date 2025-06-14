# Project Directory Structure

This document outlines the directory structure of the project.

## `diabetes_prediction`

-   `db.sqlite3`: SQLite database file.
-   `prediction/`: Main Django app for diabetes prediction functionality.
    -   `views.py`: Contains prediction logic and sugar report upload functionality.
    -   `models.py`: Database models for predictions and sugar reports.
    -   `forms.py`: Forms for prediction input and sugar report uploads.
    -   `urls.py`: URL patterns for prediction and upload functionality.
    -   `templates/`: HTML templates for prediction and upload features.
    -   `migrations/`: Database migration files.
    -   `static/`: Contains static files (CSS, JavaScript, images) for the prediction app.
    -   `ml_models/`: Likely contains the trained machine learning models used for predictions.
    -   `admin.py`: Configures the Django admin interface for prediction models.
-   `accounts/`: Django app for managing user accounts, authentication, and authorization.
    -   `views.py`: Handles user registration, login, logout, and profile management.
    -   `models.py`: Defines the database schema for user accounts and profiles.
    -   `urls.py`: Defines URL patterns for account-related actions.
    -   `forms.py`: Contains forms for user registration, login, and profile updates.
    -   `templates/`: Contains HTML templates for account-related pages.
    -   `migrations/`: Contains database migration files.
-   `dashboard/`: Django app for displaying user-specific information or application analytics.
    -   `views.py`: Logic for fetching and displaying data on the dashboard.
    -   `urls.py`: URL patterns for dashboard pages.
    -   `models.py`: Defines any database models specific to the dashboard.
    -   `templates/`: HTML templates for the dashboard.
    -   `migrations/`: Contains database migration files.
-   `diabetes_prediction/`: Main Django project configuration directory.
    -   `settings.py`: Contains the project settings, including database configuration, installed apps, middleware, etc.
    -   `urls.py`: Root URL configuration for the project, delegating to app-specific URLs.
    -   `asgi.py`: Configuration for ASGI-compatible web servers.
    -   `wsgi.py`: Configuration for WSGI-compatible web servers.
-   `media/`: Directory for user-uploaded media files.
-   `requirements.txt`: Python package dependencies.
-   `manage.py`: Django's command-line utility for administrative tasks.

## `utils`

-   `predictor.py`: Utility script, likely for making predictions.