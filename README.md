# Smart Parking System

This project is a Smart Parking System designed to address the limited parking space in our college campus by promoting carpooling. This initiative aims to reduce the number of vehicles on campus and has the potential to impact numerous people across the city. The project was developed as a group project in the 3rd year of the B.Tech CSE program.

![Home Page](/HomePage.jpg?raw=true "Home Page")

## Group Members

- **Kavya Gupta** (2101330100126)
- **Mudit Sharma** (2101330100151)
- **Shivansh Thapliyal** (2101330100213)
- **Vivek Singh** (2101330100261)

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Features

1. **Home Page**: 
   - Introduction to the carpooling system
   - Benefits of carpooling
   - How it works

2. **User Registration**:
   - Create an account
   - Login functionality

3. **Carpool Listings**:
   - View available carpool options
   - Filter by date, time, and destination

4. **Create Carpool**:
   - Allow users to create a new carpool listing
   - Specify departure time, location, and available seats

5. **Booking**:
   - Book a seat in an existing carpool
   - View booking details

6. **User Profile**:
   - View and update user information
   - Manage carpools and bookings

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd <repository-name>
    ```

3. **Set Up the Database**:
   - Create a MySQL database.
   - Import the provided SQL file (`database.sql`) to set up the necessary tables.

4. **Configure the Database Connection**:
   - Update the database connection settings in `config.php` with your MySQL credentials.

5. **Start the Server**:
   - Use a local server environment like XAMPP or WAMP to host the PHP application.
   - Place the project files in the `htdocs` directory if using XAMPP.

6. **Access the Application**:
   - Open your web browser and navigate to `http://localhost/<project-directory>`.

## Notes

- Ensure you have PHP and MySQL installed on your system.
- Use a local server environment (e.g., XAMPP, WAMP) for easier setup and configuration.
- The project is designed to be responsive and should work well on both desktop and mobile devices.

## Future Enhancements

- Integration with a real-time notification system for carpool confirmations.
- Implementation of a rating system for carpool drivers and passengers.
- Enhanced security features for user authentication and data protection.

We hope this project encourages more students to participate in carpooling and helps alleviate parking issues on our campus.
