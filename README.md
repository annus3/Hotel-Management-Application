# Hotel-Management-Application

## Overview

This repository contains code for an Android-based application for Hotel Management System.
This Android application demonstrates user authentication and registration using SQLite database.
This repository also includes code that displays hotel information and enables booking functionalities.
### Features

- **Login Activity:** Allows existing users to log in with their credentials.
- **Signup Activity:** Enables new users to create an account.
- **Booking Activity:** Enables users to book rooms.

## Setup

### Prerequisites

- Android Studio
- Android SDK
- SQLite database

### Installation

1. Clone the project and open the project in Android Studio.
2. Build and run the application on an emulator or an Android device.

## Usage

### Login Activity

The \`MainActivity\` class handles the login functionality. It includes:

- Input fields for email and password.
- Validation of user input.
- Authentication against SQLite database.
- Navigation to the main activity upon successful login.

### Signup Activity

The \`Main2Activity\` class manages the signup process. It includes:

- Input fields for username, email, and password.
- Input validation for each field.
- Addition of new users to the SQLite database.
- Snackbar notifications for successful user creation or existing user detection.


### Display Hotels (Main3Activity)

- The \`Main3Activity\` class manages the display of hotels. It includes buttons for various hotels, such as Greek Palace, Hotel JK, Mumta Palace, Holiday Inn, and Hotel Luxury. Clicking on a hotel button    navigates to the details screen.
- Displays a list of hotels.
- Allows users to view details of each hotel and proceed with booking.

### Adding Hotel Details to Database (Main4Activity)

- The \`Main4Activity\` class facilitates adding details to the database for booking. It includes fields for user information, date selection, and a confirmation button to book a room in the selected hotel.
- Collects user details and handles the booking process.
- Validates check-in and check-out dates.
- Calculates booking amount based on the selected hotel and duration.


## Viewing Booking Details (Main5Activity)

The \`Main5Activity\` class displays the details of a booking, including Booking ID, Hotel Name, Name, Phone Number, Check-In and Check-Out dates, No of Days, and Amount Paid. Users can also refresh the page to view the latest details.

## Deletion and List of Bookings (Main6Activity)

The \`Main6Activity\` class allows users to view a list of bookings and delete a booking by entering the Booking ID. The user is prompted with a confirmation dialog before deletion. Users can also refresh the list to view the latest bookings.

## Login and Signup Database (SqliteHelper)

The \`SqliteHelper\` class manages the SQLite database for user authentication. It includes functions to add a user, authenticate user credentials, and check if an email already exists.

## Hotel Database (hDBMS)

The \`hDBMS\` class handles the hotel-related database operations. It includes functions to add a booking, view all bookings, and delete a booking.


## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make changes and commit them.
4. Push changes to your branch.
5. Create a pull request.


Feel free to explore the code for detailed implementation and customization. If you encounter any issues or have suggestions, please open an issue or contact the me.
