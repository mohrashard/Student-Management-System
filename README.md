# Student Management System

## Project Overview
The **Student Management System** is a Java-based application that allows for the management of student records. This system utilizes Object-Oriented Programming (OOP) principles to ensure that the code is modular, maintainable, and scalable. The project allows users to add, update, delete, and search for student information.

### Features:
- Add a new student
- View student details
- Update existing student records
- Delete student records
- Search students by name or ID
- List all students

## Technologies Used:
- **Java**: The primary programming language used for building the system
- **Object-Oriented Programming (OOP)**: Encapsulation, inheritance, and polymorphism
- **File Handling**: To persist data between sessions (optional, if implemented)

## Project Structure:
The project is structured into multiple classes to ensure good OOP practices such as separation of concerns and modularization. The main classes are:

1. **Student**: Represents the student entity, including attributes like student ID, name, age, and course.
2. **StudentManagementSystem**: The main class that handles the user interface and interaction.
3. **StudentDatabase**: Responsible for managing the list of students and their CRUD (Create, Read, Update, Delete) operations.
4. **FileHandler**: If applicable, responsible for saving and loading student data from a file.

## Getting Started:

To run the project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mohrashard/student-management-system.git
2. **Compile and run the program**:
If you're using the command line:
javac StudentManagementSystem.java
java StudentManagementSystem
Or, if you're using an IDE like IntelliJ IDEA or Eclipse, open the project and run the StudentManagementSystem.java class directly.

##Project Report:
Please refer to the Report.docx file in the repository for a detailed explanation of the project, including UML diagrams, class relationships, and design decisions.

##How to Contribute:
1. Fork the repository
2. Create a new branch for your feature (git checkout -b feature-name)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to the branch (git push origin feature-name)
5. Create a pull request
