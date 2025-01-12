# SPL Auction System

A Django-based web application for managing player auctions in sports leagues.

## Features

- Real-time player auction management
- Team budget tracking
- Player statistics and information
- Dynamic bidding system

## Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Unix/MacOS: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Create superuser: `python manage.py createsuperuser`
7. Run the development server: `python manage.py runserver`

## Usage

1. Access admin panel at `/admin`
2. Add teams and players through the admin interface
3. Start auction at the main page
4. Monitor team budgets and player assignments