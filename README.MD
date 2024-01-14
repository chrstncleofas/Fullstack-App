# Vue.js and Django CRUD Application

## Overview

This is a simple CRUD (Create, Read, Update, Delete) application built using Vue.js for the frontend (via CDN), Django for the backend, Django Rest Framework for API development, PostgreSQL for the database, Poetry as the package manager, and Bootstrap for styling.

## Prerequisites

Make sure you have the following installed on your machine:

- Python and pip (for Django)
- Poetry (for package management)
- PostgreSQL (as the database)

## Setup

# Navigate to the backend directory
cd backend

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies using Poetry
poetry install

# Apply migrations
python manage.py migrate

# Run the Django development server
python manage.py runserver

### Frontend (Vue.js)

Since you are using Vue.js via CDN, there is no need to install npm packages. Simply include the Vue.js script in your HTML file.

```html
<!-- Include Vue.js via CDN in your frontend/index.html -->
<script src="https://cdn.jsdelivr.net/npm/vue@2"></script>
