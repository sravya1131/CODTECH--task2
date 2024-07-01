Name : MADASU SRAVYA
Company: CODTECH IT SOLUTIONS
ID: CT08SP1069
Domain: Java programming
Durartion: 25th May 2024 to 25th July 2024
Mentor: SRAVANI GOUNI
Overview
Objective
To develop a Java program that tracks and manages student grades. The program allows the user to input grades for different subjects or assignments, calculates the average grade, and displays the overall grade along with additional information such as the letter grade.

Key Components
User Input:

Collects grades from the user for different subjects or assignments.
Validates that the input grades are within the valid range (0-100).
Grade Storage:

Uses an ArrayList to store the input grades dynamically.
Calculations:

Calculates the average of the entered grades.
Determines the letter grade based on the calculated average.
Output:

Displays the total number of grades entered.
Displays the average grade.
Displays the corresponding letter grade.
Detailed Steps
Import Required Classes:

Import the Scanner class for reading user input.
Import the ArrayList class for storing grades.
Initialize Variables:

Create an ArrayList<Double> to store grades.
Create a Scanner object to read input from the user.
Declare a variable choice to control the loop for grade entry.
Grade Input Loop:

Use a do-while loop to repeatedly prompt the user to enter grades.
Inside the loop, prompt the user to enter a grade.
Check if the entered grade is between 0 and 100. If valid, add the grade to the ArrayList; otherwise, display an error message.
Ask the user if they want to enter another grade. Continue the loop if the user responds with "yes".
Calculate Average Grade:

Sum all the grades in the ArrayList.
Calculate the average by dividing the total sum by the number of grades.
Determine Letter Grade:

Use a series of conditional statements (if-else if) to assign a letter grade based on the average:
90-100: A
80-89: B
70-79: C
60-69: D
Below 60: F
Display Results:

Print the total number of grades entered.
Print the average grade.
Print the corresponding letter grade.
Close Scanner:

Close the Scanner object to free up resources.
Example Program Flow
The user is prompted to enter grades one by one.
The user decides whether to continue entering grades or not after each entry.
Once the user finishes entering grades, the program calculates the average of all entered grades.
The program determines the letter grade based on the calculated average.
The program displays the total number of grades, the average grade, and the corresponding letter grade.
This Java program provides a basic but functional way to manage and evaluate student grades. It can be further enhanced by adding features like managing grades for multiple students, storing and retrieving grades from a file, or calculating additional statistics.
![Screenshot (7)](https://github.com/sravya1131/CODTECH--task2/assets/112858180/0d37b57c-d17c-432e-b3c7-754961826ce4)
