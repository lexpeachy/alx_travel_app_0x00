# ALX Travel App

A vacation rental platform built with Django and Django REST framework.

## Setup

1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations: `python manage.py migrate`
5. Seed the database: `python manage.py seed`
6. Run the development server: `python manage.py runserver`

## Database Models

- **Listing**: Vacation rental properties
- **Booking**: Reservations made by users
- **Review**: User reviews for listings

## API Endpoints

- `/api/listings/` - List and create listings
- `/api/listings/<id>/` - Retrieve, update, or delete a listing
- `/api/bookings/` - List and create bookings
- `/api/bookings/<id>/` - Retrieve, update, or delete a booking