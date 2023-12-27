# Hospital-Management-System
This Hospital Management System is a Java-based application that facilitates various administrative tasks within a hospital environment. The system integrates with a PostgreSQL database to manage doctors, patients, appointments, medical histories, and schedules efficiently.

## Setup Instructions

1. **Database Setup**: Create a PostgreSQL database and execute the SQL files provided in the repository to set up the necessary tables and functions.
   
2. **Java Configuration**: Ensure you have Java installed on your system. Use an IDE or command line to compile and run the Java code provided.

3. **Running the Application**: Execute the `Main` class to launch the Hospital Management System.

## Features

- **Insert Data**: Add new doctors and patients to the system.
- **Manage Appointments**: View available appointments and schedule patients.
- **Retrieve Information**: Access details about doctors, patients, and their medical histories.
- **Schedule Management**: Check doctor schedules and the overall hospital schedule.

## Usage

Upon running the application, you will be prompted with various controls:

- Enter the respective number to perform actions like inserting doctors or patients, viewing schedules, appointments, and more.
- Follow the prompts to input relevant information when prompted for doctor or patient details.

## Database Schema

The system utilizes a PostgreSQL database with the following tables:

- **Patient**: Stores patient details.
- **Medical_History**: Records medical histories of patients.
- **Schedule**: Contains time schedules.
- **Doctors**: Holds information about doctors.
- **Appointments**: Manages appointments between patients, schedules, and doctors.
- **Follow**: Tracks relationships between schedules and doctors.

## Code Overview

The `Main` class contains the main logic for user interaction. It establishes a connection to the database and provides a menu-driven interface for different functionalities.

Various functions within the `DBFunctions` class handle database interactions, including inserting data, retrieving information, and managing appointments.

## Important Notes

- Ensure proper database connectivity before using the system.
- Validate input to prevent errors or inconsistencies in the database.

## Credits

This project was developed by Asad Alam as part of the DBMS course.

## Contributors

- Shiva Koshta

