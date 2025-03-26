# School Management System

## Overview
The **School Management System** is a Java-based desktop application designed to efficiently manage school administration tasks. It includes features for managing students, teachers, and administrative staff, providing an interactive GUI for seamless user experience.

## Features
- **User Authentication**: Secure login system for admins, teachers, and students.
- **Student Management**: Add, edit, and remove student details.
- **Teacher Management**: Manage teacher profiles and assignments.
- **Administrative Functions**: Register school administrators and control system settings.
- **Database Connectivity**: Uses a relational database for secure and persistent data storage.

## Technologies Used
- **Java (Swing & AWT)** for the graphical user interface
- **MySQL** for the database management
- **JDBC** for database connectivity
- **Apache Ant** for project build automation

## Installation & Setup

### Prerequisites
Ensure you have the following installed on your system:
- Java Development Kit (JDK 8 or higher)
- Apache NetBeans IDE (or any preferred Java IDE)
- MySQL Server
- Apache Ant (if using manual build)

### Steps to Run the Project
1. **Clone or Extract the Project**
   ```sh
   git clone <https://github.com/Lakshan-Dananjana/School-Management-System-Project-Final.git>
   ```
   OR extract the provided ZIP file.

2. **Import Project into NetBeans**
   - Open NetBeans IDE
   - Click on `File > Open Project` and select the extracted folder

3. **Configure the Database**
   - Create a new MySQL database (e.g., `school_db`)
   - Update database credentials in `src/Code/DBconnection.java`
   - Import the SQL file (if provided) into MySQL

4. **Build & Run**
   - If using NetBeans, click `Run > Run Project`
   - If using Apache Ant, navigate to the project directory and run:
     ```sh
     ant build
     ant run
     ```

## Contributors
- **Lakshan Dananjana Weerasinghe** - Developer

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

