Employee Management System

A simple Java-based console application to manage employee records.
This system allows adding, searching, editing, deleting, and displaying employees. Data is persisted using file handling and object serialization.

Features

📌 Add Employee – Store employee details (ID, name, salary, contact number, email).

🔍 Search Employee – Look up employees by ID.

✏️ Edit Employee – Update employee details.

❌ Delete Employee – Remove employee records.

📋 Display All Employees – View the complete employee list in tabular format.

💾 Data Persistence – Records are saved in a file (test.txt) using serialization.

Technologies Used

Java (Core Java, OOP concepts)

File Handling & Serialization

Collections Framework (ArrayList)

Setup & Installation

Clone/Download this project.

Open the project in any Java IDE (Eclipse, IntelliJ, NetBeans) or terminal.

Compile the program:

javac EmployeeManagement.java


Run the program:

java EmployeeManagement

File Storage

Employee data is stored in:

C:/Users/anush/Desktop/java project/test.txt


You can update the file path inside EmployeeManagement.java if needed.

Example Usage
********* Welcome to the Employee Management System **********

1). Add Employee to the Database
2). Search for Employee
3). Edit Employee details
4). Delete Employee Details
5). Display all Employees
6). EXIT

Enter your choice :

Future Improvements

Switch to database (MySQL/SQLite) instead of text file for scalability.

Add GUI (JavaFX / Swing) for better user experience.

Implement authentication & roles (e.g., admin vs user).

Add export/import to CSV/Excel.
