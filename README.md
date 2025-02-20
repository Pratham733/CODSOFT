# Number Guessing Game

A simple **Java-based Number Guessing Game** where the user tries to guess a randomly generated number within a limited number of attempts. The game provides feedback and tracks the user's score across multiple rounds.

![Screenshot 2025-02-10 001033](https://github.com/user-attachments/assets/b2124905-4dff-4c38-bbff-8cc181fb0faf)


## Features
- Random number generation (1-100)  
- Limited attempts (default: 7)  
- Hints if the guess is **too high** or **too low**  
- Supports multiple rounds  
- Tracks the **player's score**  
- User-friendly **console interface** 


# Student Grade Calculator

![Screenshot 2025-02-10 093036](https://github.com/user-attachments/assets/478cd33a-026c-4ffb-a181-9134dbf9cd9d)


## Description
This Java program calculates a student's grade based on marks obtained in multiple subjects. It takes input from the user, computes the total marks, average percentage, and assigns a grade accordingly.

## Features
- Accepts user input for the number of subjects.
- Ensures valid marks (0-100) are entered.
- Computes total marks and average percentage.
- Assigns grades based on predefined percentage ranges.
- Displays the final results including total marks, percentage, and grade.


## Grading Criteria
| Percentage | Grade |
|------------|-------|
| 90% - 100% | A+    |
| 80% - 89%  | A     |
| 70% - 79%  | B     |
| 60% - 69%  | C     |
| 50% - 59%  | D     |
| Below 50%  | F     |


# ATM Interface in Java
This project is a simple ATM Interface implemented in Java. It allows users to perform basic banking operations such as checking balance, depositing money, and withdrawing money through a console-based menu system.

![Screenshot 2025-02-14 091507](https://github.com/user-attachments/assets/83ee1ffb-a2d2-4158-b494-88a45f0e451f)


Features
Check Balance: Display the user's current account balance.
Deposit Money: Add a specified amount to the account balance.
Withdraw Money: Deduct a specified amount from the balance if sufficient funds are available.
Input Validation: Ensures only valid transactions are processed.
How It Works
The program initializes with a default account balance.
Users are presented with a menu to choose an action (e.g., check balance, deposit, withdraw).
Based on the user’s choice, the program processes the request and displays the result.
The menu repeats until the user chooses to exit.

--- ATM Menu ---
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit


# Quiz Application with Timer

This is a simple command-line quiz application written in Java. It presents multiple-choice questions to users, limits the time allowed to answer each question, and calculates the final score based on correct answers.

![image](https://github.com/user-attachments/assets/5ac570ae-c26d-4270-9b81-ff9bea7ebfab)


Features

Quiz Questions and Options: Stores multiple questions with four options each.

Timer: Limits the time to answer each question (default is 10 seconds).

Question Display: Presents one question at a time.

Answer Submission: Allows users to input their answer choice.

Score Calculation: Tracks the user's score based on correct answers.

Result Display: Shows the final score and the correct answers for incorrect responses.



# Student Course Registration System

This is a simple **Student Course Registration System** implemented in Java. It allows students to register for courses, drop courses, and view registered courses.

## Features
- **Course Database**: Store course information, including course code, title, description, capacity, and schedule.
- **Student Database**: Store student information, including student ID, name, and registered courses.
- **Course Listing**: Display available courses with details and available slots.
- **Student Registration**: Allow students to register for courses from the available options.
- **Course Removal**: Enable students to drop courses they have registered for.


## Usage
1. **Display Available Courses**: Lists all the courses with details like title, schedule, and available slots.
2. **Register for a Course**: Allows the student to register for a course by entering the course code.
3. **Drop a Course**: Enables the student to drop a registered course.
4. **View Registered Courses**: Displays the list of courses the student has registered for.

## Sample Courses
- `CS101` - Introduction to Computer Science
- `MA101` - Calculus I
- `PH101` - Physics I

## Example Interaction
1. Select option `1` to view available courses.
2. Register for a course by selecting option `2` and entering the course code.
3. Drop a course using option `3`.
4. View registered courses using option `4`.
5. Exit the system by selecting option `5`.

## Future Enhancements
- Integration with a real database for persistence.
- Support for multiple students.
- Enhanced user interface.

