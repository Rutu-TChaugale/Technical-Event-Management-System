# Technical Event Management System

## Overview
The **Technical Event Management System** is a simple console-based Java application that allows users to register for various events, filter students based on event type or name, and count the number of registered students for specific events. The system ensures unique registrations and validates event types.

## Features
- **Register for an Event**: Users can register by providing their ID, age, name, and event type.
- **Filter Students by Event Type**: Display all students registered for a specific event.
- **Filter Students by Name**: Retrieve student details by searching for their name.
- **Count Students for a Specific Event**: Get the number of students registered under a given event category.
- **Validation**: Ensures unique student IDs and allows only predefined event types (Technical, Cultural, Sport).

## Technologies Used
- Java
- Scanner (for user input handling)

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Open the project in any Java IDE (Eclipse, IntelliJ, or VS Code) or use a terminal.
3. Compile and run the project:
   ```sh
   javac -d . com/tems/Client/Client.java com/tems/Controller/Controller.java
   java com.tems.Controller.Controller
   ```

## Project Structure
```
com.tems
│── Client
│   └── Client.java
│── Controller
│   └── Controller.java
```



