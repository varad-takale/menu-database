# menu-database

Java Database Management System using JDBC and MySQL is a console-based application developed using Core Java, JDBC, SQL, and MySQL. The project demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations for managing user registration records in a relational database.

The application provides a menu-driven console interface through which users can insert new records, display all existing records, update user information, and delete records based on User ID. The Start class works as the main entry point and controls the application flow, while the DAO class manages the connection between the Java application and the MySQL database.

Separate classes are implemented for each database operation, making the project modular and easier to understand. InsertIntoDatabase handles record insertion, DisplyAllRecords retrieves and displays records, UpdateDatabaseRecords modifies existing user information, and DeleteFromDatabase removes records from the database. JDBC PreparedStatement is used for executing SQL queries with user-provided values.

This project is useful for understanding Java JDBC, MySQL connectivity, SQL queries, PreparedStatement, ResultSet, CRUD operations, exception handling, console-based input, and basic database application architecture. It serves as a practical example of connecting a Java application with a relational database and performing fundamental database management operations.
