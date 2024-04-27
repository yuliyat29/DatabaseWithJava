<img width="1416" alt="Screenshot 2024-04-27 at 17 36 04" src="https://github.com/yuliyat29/DatabaseWithJava/assets/124449536/e19bfef7-4d1f-48d4-a2dd-528810e4000b">

# Java Database Project

## Description

This Java project demonstrates how to interact with a database using JDBC (Java Database Connectivity). It includes sample code for connecting to a database, performing CRUD (Create, Read, Update, Delete) operations, and handling exceptions.

## Requirements

- Java Development Kit (JDK) 8 or higher
- MySQL Database Server (or any other supported database)
- JDBC Driver for your database (e.g., MySQL Connector/J)

## Setup

1. **Database Setup**:
   - Install and configure your database server (e.g., MySQL).
   - Create a new database and table(s) as per your requirements.
   - Update the database connection URL, username, and password in the Java code accordingly.

2. **JDBC Driver**:
   - Download the JDBC driver for your database and include it in your project's classpath.

## Usage

1. **Database Connection**:
   - Initialize a connection to your database using the JDBC driver.
   - Use the `DriverManager.getConnection()` method to establish a connection.

2. **CRUD Operations**:
   - Use JDBC `Statement` or `PreparedStatement` to execute SQL queries.
   - Perform Create, Read, Update, and Delete operations as needed.

3. **Exception Handling**:
   - Handle SQLExceptions that may occur during database interactions.
   - Use try-catch blocks to gracefully handle exceptions and close resources properly.

## Example

```java
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;

public class Main {
    public static void main(String[] args) {
        // Database connection parameters
        String url = "jdbc:mysql://localhost:

