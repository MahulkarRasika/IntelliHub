# IntelliHub
IntelliHub is a Java-based smart device management system that allows users to add, view, update, and delete various smart home devices.

# IntelliHub

IntelliHub is a smart device management system designed to monitor, control, and manage a variety of smart home devices. This project showcases basic operations like creating, reading, updating, and deleting devices, and offers a foundation for building a more complex smart home ecosystem.

## Features

- **Add Devices:** Add new smart devices with attributes such as name, real-time monitoring capability, settings, and type.
- **View Devices:** Retrieve and display information about all registered devices.
- **Update Devices:** Modify the configurations or attributes of existing devices.
- **Delete Devices:** Remove devices that are no longer in use.
- **Basic Error Handling:** Handles basic SQL exceptions and errors.

## Technologies Used

- **Java**: Core programming language used for developing the application.
- **JDBC**: Java Database Connectivity for managing database operations.
- **MySQL**: Relational database management system for storing and managing device data.

## Database Schema

The project uses a MySQL database with a table called `devices`. The table schema is as follows:

```sql
CREATE TABLE devices (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    realtimemonitoring VARCHAR(100),
    setting VARCHAR(100),
    type VARCHAR(100)
);


