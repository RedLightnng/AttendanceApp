# Face Recognition Attendance System

# Basic Requirements
- Python
- Mysql (you will need to change the password and username of the SQL database in the code, or you can just set your MySQL user as `root` and password as `1234`)
- Camera
- Appropriate libraries detailed below
- Some randon IDE
- 🧠

## Overview
This is a Python-based system for automating student attendance management through facial recognition technology. It offers an efficient and convenient way to keep track of student attendance, utilizing the following libraries and technologies:

- OpenCV for camera access and video processing.
- Face Recognition for facial recognition and identification.
- MySQL Connector for database integration.
- Tkinter for the user interface.

## Features
- Start and stop the camera to capture student faces.
- Mark attendance for recognized students.
- Add new students with their details and face images.
- View and manage student attendance records.

## How to Use
1. Clone the repository.
2. Install the required Python libraries (OpenCV, face_recognition, mysql-connector-python).
3. create a database called `faces` and create two tables in it. Namely `student_details` & `attendance`
4. `CREATE TABLE student_details (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL, facepath VARCHAR(255) NOT NULL);`
5. `CREATE TABLE attendance (id INT AUTO_INCREMENT PRIMARY KEY, student_id INT NOT NULL, student_name VARCHAR(255) NOT NULL, attendance_time DATETIME NOT NULL);`
7. Run the `MainAttendanceApp.py` script to start the application.


## Contributing
Contributions and improvements to this project are welcome. Feel free to fork the repository, make changes, and create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
