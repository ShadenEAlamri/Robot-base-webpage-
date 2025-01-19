# Robot-base-webpage-

## Overview

This web-based application allows users to control a robotic base's movement using a simple interface. It supports sending directional commands and retrieving the last command sent.

## Features

- Control the robot in four directions: Forward, Backward, Left, Right.
- Stop the robot with a dedicated button.
- Retrieve the last direction command sent.

## Technologies Used

- HTML, CSS, JavaScript
- PHP, MySQL
- XAMPP (local server)

## Setup Instructions

1. **Install XAMPP**:
   - Download and install from the [official XAMPP website](https://www.apachefriends.org/index.html).

2. **Start XAMPP**:
   - Open XAMPP Control Panel and start Apache and MySQL.

3. **Create Database**:
   - Open `http://localhost/phpmyadmin`.
   - Create a database named `robot_control`.
   - Create a table `directions` with columns:
     - `id` (INT, AUTO_INCREMENT, PRIMARY KEY)
     - `direction` (VARCHAR(10))

4. **Project Files**:
   - In `htdocs/robot_project`, create:
     - `index.html`: Main interface for controlling the robot.
     - `send_direction.php`: Handles command storage.
     - `get_last_direction.php`: Retrieves the last command.

## Conclusion

This project demonstrates a simple method for controlling a robotic base with a web interface, integrating front-end and back-end technologies.

## License

Open-source for personal and educational use.
