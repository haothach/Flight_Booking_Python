# Flight Booking System

This is a **Flight Booking System** built with **Python**, **MySQL**, and **JavaScript**. The system allows users to search for flights, book tickets, and manage bookings. It is designed to provide a web-based interface to interact with flight data stored in a MySQL database.

## Features

- **User Registration**: Users can register and log in to book flights.
- **Search Flights**: Search available flights by departure and destination.
- **Book Flight**: Users can book flights by selecting available options.
- **View Bookings**: Users can view their past bookings.
- **Cancel Booking**: Users can cancel a flight booking.

## Requirements

- **Python 3.x**
- **MySQL 5.x or higher**
- **MySQL Connector for Python** (`mysql-connector-python`)

### Setup Instructions  
Clone the repository:  
```bash
git clone https://github.com/haothach/Flight_Booking_Python.git
```
### Dependencies  
Install the required libraries using `pip`:  
```bash
pip install -r requirements.txt
```
### IMPORTANT:
### Replace the following MySQL and Cloudinary credentials with your own before running the application.

```bash
app.secret_key = 'your_secret_name'
app.config["SQLALCHEMY_DATABASE_URI"] = "mysql+pymysql://root:%s@your_MySQL_user/flight?charset=utf8mb4" % quote("your_password")


cloudinary.config(
    cloud_name='your_cloud_name',
    api_key='your_api_key',
    api_secret='your_api_secret'
)
```
