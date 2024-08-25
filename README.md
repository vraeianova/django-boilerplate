# Django Boilerplate

This repository contains a boilerplate for Django projects, designed to provide a well-structured foundation that allows for agile and organized development. This boilerplate is intended to simplify the initial setup of the project and ensure best practices from the start.

## Project Structure

The project structure is organized as follows:

```plaintext
django-boilerplate/
├── .venv/               # Virtual environment
├── src/
│   ├── __pycache__/     # Python-generated cache files
│   ├── conf/            # Project configuration
│   │   ├── settings/    # Modularized settings
│   │   │   ├── __init__.py
│   │   │   ├── base.py  # Base settings
│   │   │   ├── development.py  # Development-specific settings
│   │   ├── __init__.py
│   │   ├── asgi.py      # ASGI configuration
│   │   ├── urls.py      # URL routing
│   │   ├── wsgi.py      # WSGI configuration
│   ├── db.sqlite3       # SQLite database (default)
│   ├── manage.py        # Django management script
├── tests/               # Directory for tests
├── .env                 # Environment variables (not versioned)
├── .gitignore           # Git ignored files and directories
├── LICENSE              # Project license
├── pdm.lock             # PDM dependency lock file
├── pyproject.toml       # PDM configuration file
└── README.md            # Project documentation
