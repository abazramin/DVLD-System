# Driving & Vehicle License Management System (DVLD)

## Introduction
The Driving & Vehicle License Management System is designed to streamline the process of issuing, renewing, and managing driver licenses. It provides a secure and user-friendly experience for users. The system is built using C#, SQL Server, ADO.NET, and follows a 3-Tier Architecture for optimal performance and maintainability.

---

## Key Features
- Issue new licenses.
- Renew licenses.
- Reprint licenses.
- Cancel licenses.
- Replace damaged licenses.
- User-friendly interface for staff and users.

---

## Prerequisites

### Software Requirements:
1. Visual Studio (any version supporting .NET Framework).
2. SQL Server (to manage the database).
3. ADO.NET (integrated with the project for database connectivity).

---

## Installation and Setup

1. Clone the Project:
   `bash
   git clone <https://github.com/abazramin/Drive-License-System-Mangments.git>

2. Set up the Database:

Import the database file (if provided) into SQL Server.

Update the database connection in the project to match your local server configuration.



3. Open the Project in Visual Studio:

Open the solution file using Visual Studio.

Ensure all necessary packages (such as ADO.NET) are installed.



4. Modify the Connection String:

Locate the file responsible for the Connection String (typically in the app settings).

Update it with your server name and database credentials.



5. Run the Application:

Press Start in Visual Studio to run the project.





---

## Project Structure

Forms: User interfaces for various operations (issuing, renewing, reprinting, and canceling licenses).

Data Layer: Handles database connectivity and operations.

Business Layer: Implements business rules and data processing.

Presentation Layer: The graphical user interface for users.



---

## Architecture (3-Tier)

1. Presentation Layer:

Handles user interaction (Forms).



2. Business Logic Layer (BLL):

Processes data and implements business rules.



3. Data Access Layer (DAL):

Manages interactions with the database using ADO.NET.





---

## How to Contribute

Contributions are welcome via Pull Requests.

For issues and suggestions, please open an Issue in the repository.



---

## Notes

- Ensure the Connection String is updated before running the application.

- For more information or support, feel free to contact me via the Issues section on the repository.
