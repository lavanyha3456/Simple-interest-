# Simple-interest-
CODING:

import java.util.Scanner;

public class SimpleInterestCalculator {

public static void main(String[] args) {

// Create a Scanner object for user input

Scanner scanner = new Scanner(System.in);

// Prompt user to enter the principal amount

System.out.print("Enter the principal amount: ");

double principal = scanner.nextDouble();
// Prompt user to enter the rate of interest

System.out.print("Enter the rate of interest (in %): ");

double rate = scanner.nextDouble();

// Prompt user to enter the time in years

System.out.print("Enter the time (in years): ");

double time = scanner.nextDouble();

// Calculate the simple interest

double simpleInterest = (principal * rate * time) / 100;

// Display the result

System.out.println("The Simple Interest is: " + simpleInterest);

// Close the scanner

scanner.close();

}

}

OUTPUT:

Enter the principal amount: 1000

Enter the rate of interest (in %): 5

Enter the time (in years): 2

The Simple Interest is: 100.0
