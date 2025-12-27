# NailOps

NailOps is a Django-based nail salon operations web application.
It is designed as a portfolio project demonstrating clean architecture,
professional Git workflow, and production-style development practices.

## Features
- Service listing
- Appointment booking
- Customer appointment tracking
- Staff scheduling (upcoming)
- Role-based access (upcoming)

## Tech Stack
- Python
- Django
- SQLite (development)

---

## Local Setup (Windows)

Run the following commands in order to start the project locally:

```bash
# Create virtual environment
python -m venv .venv

# Activate virtual environment
.\.venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
py manage.py migrate

# Run development server
py manage.py runserver
