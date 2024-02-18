# Bus Ticket Booking System - Django

Welcome to the Bus Ticket Booking System built with Django! This web application allows users to easily book and manage bus tickets online.

## About the Online Bus Reservation System

This project is an Online Bus Reservation System developed using the following technologies:

- Python
- Django
- HTML
- CSS
- JavaScript
- jQuery
- Ajax
- Bootstrap v5
- Material Design Bootstrap Template
- Font-Awesome

### Features

**Management-Side:**
- Login
- Home/Dashboard Page (Displays the summary)
- Categories Management
  - Add New Category
  - List All Categories
  - Update Category Details
  - Delete Category Details
- Location Management
  - Add New Location
  - List All Locations
  - Update Location Details
  - Delete Location Details
- Bus Management
  - Add New Bus
  - List All Buses
  - Update Bus Details
  - Delete Bus Details
- Trip Schedules Management
  - Add New Trip Schedule
  - List All Trip Schedules
  - Update Trip Schedule Details
  - Delete Trip Schedule Details
- Bookings Management
  - Add New Trip Booking
  - List All Trip Bookings
  - Update Trip Booking Details
  - Delete Trip Booking Details
- Profile
  - Update Profile Details
  - Update Account Password
- Logout

**Public-Side:**
- Home Page
- Find Trip Schedules
- List All Upcoming Trip
- Book or Reserve a Seat to a Trip

### Sample Snapshots

![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/03465c43-0fd0-42c4-b3de-f9fe571bbc02)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/52420406-c4de-41f2-abbe-946659739036)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/01c0d1ca-de12-41b5-b523-b0158018c015)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/e795057b-6ded-4236-949f-882055166fe8)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/8bdbb713-5b9b-46e5-b462-6bff4b5ee7c6)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/3cb2ea32-7003-4696-9a26-e604f10fc121)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/9ca4d2d8-6eb7-4b09-93ca-42dfce5ecf03)
![image](https://github.com/Bikash012/bus-ticket-booking-system-django/assets/101698546/f699fe46-316a-440d-adb7-238122a1adb0)


## How to Run

### Download/Install the following
- Python (I used v3.12.2)
- Django (I used v5.0.2)
- PIP (for Python modules installation)

### Setup/Installation
1. Open your Terminal/Command Prompt window. (make sure to add "python" and "pip" in your environment variables)
2. Change the working directory to the extracted source code folder. i.e. `cd C:\Users\Netro\Desktop\Hamro FInal Project\bus_booking_django`
3. Run the following commands:
   ```bash
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
