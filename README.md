# Student Result Management System

This program is a simple Student Result Management System implemented in Java. It allows users to enter student details, display student information, calculate and display student results (percentage), and exit the program.

## Interface Exam
The Exam interface is used to define a common method Percent_cal() for calculating the percentage of a student's marks. By implementing this interface, classes can ensure consistency in calculating percentages for different types of students.

### Definition:
The `Exam` interface defines a method `Percent_cal()` that calculates the percentage of a student's marks.

## Student Class
The Student class represents a basic entity in the system, encapsulating information about a student such as name, roll number, and marks for two subjects. It provides methods to access and modify student attributes and a toString() method for generating a string representation of a student object

### Definition:
The `Student` class represents a student with attributes such as name, roll number, and marks for two subjects.

### Constructor:
- `Student(String name, int roll_no, double mark1, double mark2)`: Initializes a student with the provided details.

### Methods:
- Getter and setter methods for each attribute.
- `toString()`: Method to generate a string representation of the student object.

## Result Class

### Definition:
The `Result` class extends the `Student` class and implements the `Exam` interface. It calculates the percentage of a student's marks and displays the result.

### Constructor:
- `Result()`: Initializes an empty `Result` object.

### Methods:
- `Percent_cal()`: Method to calculate the percentage of a student's marks.
- `enterStudentDetails(Scanner scanner)`: Method to enter student details interactively using a `Scanner`.
- `displayStudentInfo()`: Method to display student information.
- `displayResult()`: Method to display the result, including the percentage.
- `toString()`: Method to generate a string representation of the result object.

## Main Class
The Result class extends the Student class and implements the Exam interface. It enhances the basic student functionality by adding the ability to calculate and display the percentage of marks. This class leverages inheritance to reuse the attributes and methods defined in the Student class, providing a seamless extension.

### Definition:
The `Main` class contains the `main` method and serves as the entry point for the program.

### Methods:
- `main(String[] args)`: Entry point of the program. Provides a menu-driven interface for users to interactively enter student details, display student information, display results, and exit the program.



