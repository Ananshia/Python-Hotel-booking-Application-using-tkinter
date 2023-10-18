
# Hotel Reservation App

This is a simple hotel reservation application built using Python and the Tkinter library. The application allows users to sign up, log in, and make hotel room reservations. Here's a brief overview of the application and its functionality.

## Getting Started

To run the application, make sure you have Python installed on your system. You will also need to install the required libraries mentioned in the code:

- tkinter
- sqlite3
- PIL (Pillow)
- tkcalendar

You can install these libraries using pip:

```
pip install tkinter sqlite3 pillow tkcalendar
```

After installing the required libraries, you can run the application by executing the Python script.

```
python hotel_reservation_app.py
```

## Features

### Main Window

- The main window of the application displays a background image of a luxury hotel.
- Users can sign up or log in to the system by clicking the corresponding buttons.

### Sign Up

- Users can create a new account by clicking the "SIGN UP" button.
- The sign-up form includes fields for first name, last name, phone number, email, create password, and confirm password.
- Validation checks are performed to ensure all fields are filled, and passwords match.
- User data is stored in a SQLite database.

### Log In

- Users can log in to their accounts by clicking the "LOGIN" button.
- The log-in form includes fields for username and password.
- A sample username and password are provided in the code for testing.
- Users can access the hotel reservation page upon successful login.

### Hotel Reservation

- After logging in, users can view hotel room details and select a room for booking.
- Room details include room type, amenities, and rates.
- Users can choose the number of nights, adults, and rooms for their reservation.
- A calendar widget allows users to select check-in and check-out dates.
- The selected dates are displayed in the respective entry fields.
- Users can confirm their check-in and check-out dates by clicking the "CONFIRM CHECK-IN" and "CONFIRM CHECK-OUT" buttons.
- Upon confirming all reservation details, users can click the "CONFIRM" button to complete the booking.
- Booking information is stored in a SQLite database.

### Navigation

- Users can navigate between room types by clicking the ">>" and "<<" buttons on the room details page.


## Author

- ANANSHIA PEARL



## Acknowledgments

- Special thanks to the Anantara Resorts, Tkinter, Pillow, and tkcalendar libraries for making GUI development in Python easier.
- This project is for educational purposes and can be extended with additional features and improvements.

Feel free to enhance and customize this application as needed for your use case. Enjoy exploring and experimenting with Python GUI development!
