# Hotel-Management-Application
#!/bin/bash

cat <<EOF
# Android Login and Signup Activities

This repository contains code for Android login and signup functionalities.

## Overview

This Android application demonstrates user authentication and registration using SQLite database.

### Features

- **Login Activity:** Allows existing users to log in with their credentials.
- **Signup Activity:** Enables new users to create an account.

## Setup

### Prerequisites

- Android Studio
- Android SDK
- SQLite database

### Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/your_username/your_repository.git
   \`\`\`

2. Open the project in Android Studio.
3. Build and run the application on an emulator or an Android device.

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

## Contributing

Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (\`git checkout -b feature/awesome-feature\`).
3. Make changes and commit them (\`git commit -am 'Add some feature'\`).
4. Push the changes to your branch (\`git push origin feature/awesome-feature\`).
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

Special thanks to the contributors and any libraries used in this project.

---

Feel free to explore the code for detailed implementation and customization. For any issues or suggestions, please open an issue or contact [maintainer's email]. Enjoy exploring the login and signup functionalities in Android!

# Android Hotel Display and Booking

This repository includes code for an Android application that displays hotel information and enables booking functionality.

## Overview

The project consists of two activities:

### Display Hotels (Main3Activity)

- Displays a list of hotels.
- Allows users to view details of each hotel and proceed with booking.

### Adding Hotel Details to Database (Main4Activity)

- Collects user details and handles the booking process.
- Validates check-in and check-out dates.
- Calculates booking amount based on the selected hotel and duration.

## Usage

### Display Hotels

The \`Main3Activity\` class manages the display of hotels. It includes buttons for various hotels, such as Greek Palace, Hotel JK, Mumta Palace, Holiday Inn, and Hotel Luxury. Clicking on a hotel button navigates to the details screen.

### Adding Details to Database

The \`Main4Activity\` class facilitates adding details to the database for booking. It includes fields for user information, date selection, and a confirmation button to book a room in the selected hotel.

## Contributing

Contributions to enhance features or fix issues are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch (\`git checkout -b feature/awesome-feature\`).
3. Make changes and commit them (\`git commit -am 'Add some feature'\`).
4. Push changes to your branch (\`git push origin feature/awesome-feature\`).
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore the code for detailed implementation and customization. For any issues or suggestions, please open an issue or contact the project maintainer. Enjoy exploring the hotel display and booking functionalities in Android!

# Hotel Management System (HMS) Android App

This repository contains the source code for a Hotel Management System Android app. The app includes features such as hotel information display, booking, viewing and deletion of bookings, and user authentication.

## Table of Contents

- [Viewing Booking Details (Main5Activity)](#viewing-booking-details)
- [Deletion and List of Bookings (Main6Activity)](#deletion-and-list-of-bookings)
- [Login and Signup Database (SqliteHelper)](#login-and-signup-database)
- [Hotel Database (hDBMS)](#hotel-database)

## Viewing Booking Details (Main5Activity)

The \`Main5Activity\` class displays the details of a booking, including Booking ID, Hotel Name, Name, Phone Number, Check-In and Check-Out dates, No of Days, and Amount Paid. Users can also refresh the page to view the latest details.

## Deletion and List of Bookings (Main6Activity)

The \`Main6Activity\` class allows users to view a list of bookings and delete a booking by entering the Booking ID. The user is prompted with a confirmation dialog before deletion. Users can also refresh the list to view the latest bookings.

## Login and Signup Database (SqliteHelper)

The \`SqliteHelper\` class manages the SQLite database for user authentication. It includes functions to add a user, authenticate user credentials, and check if an email already exists.

## Hotel Database (hDBMS)

The \`hDBMS\` class handles the hotel-related database operations. It includes functions to add a booking, view all bookings, and delete a booking.

## Getting Started

1. Clone the repository.
2. Open the project in Android Studio.
3. Run the app on an emulator or Android device.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch (\`git checkout -b feature/awesome-feature\`).
3. Make changes and commit them (\`git commit -am 'Add some feature'\`).
4. Push changes to your branch (\`git push origin feature/awesome-feature\`).
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the code for detailed implementation and customization. If you encounter any issues or have suggestions, please open an issue or contact the project maintainer.
EOF
