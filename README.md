# SalaryCalculator it's will be calculator hourly rate and hours worked
 The program starts by importing the Scanner class from the java.util package
 which allows the user to enter input.
Next the main method is defined which is the entry point of the program
Inside the main method a new Scanner object is created to read input 
 Then, the user is prompted to enter the basic salary of the employee 
The input is read using the nextInt method of the Scanner class and stored in an integer variable 
Next the program calculates the  salary based on the basic salary using the following formula:
 double baseSalary = hourlyRate * hoursWorked;
 double overtimeRate = 1.5 * hourlyRate;
 double overtimeHours = Math.max(0, hoursWorked - 40);
 double overtimePay = overtimeHours * overtimeRate;
