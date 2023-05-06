# Factorial-Exception

This package contains two classes: Factorial and Demo that demonstrate how to use exception handling in Java.

FactorialException Class
This class extends the Exception class and is used to throw an exception when the input number for factorial calculation is out of the range 0-15.

Constructor
FactorialException(int number): constructs a new FactorialException object with the given number.
Methods
toString(): returns a string representation of the exception, indicating the number that caused the exception.
Factorial Class
This class is used to calculate the factorial of input numbers using the FactorialException class to handle input errors.

Methods
main(String[] args): The main method of the Factorial class reads input numbers as arguments and calculates their factorial. If an input number is out of range, it throws a FactorialException. If there is a NumberFormatException, it catches and prints the exception. If there is a FactorialException, it catches and prints the exception.
NOMATCHEXCP Class
This class extends the Exception class and is used to throw an exception when the input string is not equal to "India".

Constructor
NOMATCHEXCP(int lineNo, String inputString): constructs a new NOMATCHEXCP object with the given lineNo and inputString.
Methods
None
Demo Class
This class is used to demonstrate how to use the NOMATCHEXCP class to handle input errors.

Methods
main(String[] args): The main method of the Demo class reads an input string and checks if it is equal to "India". If it is not, it throws a NOMATCHEXCP. If there is an ArrayIndexOutOfBoundsException, it catches and prints the exception. If there is a NOMATCHEXCP, it catches and prints the exception.
Usage
To use these classes, import the ExceptionDemo package and use the Factorial and Demo classes in your Java program. Call the main() method of the Factorial class with input numbers as arguments to calculate their factorial. Call the main() method of the Demo class with an input string to check if it is equal to "India".
