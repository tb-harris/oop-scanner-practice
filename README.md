# Scanner Practice

## TempConverter.java
* Ask the user for a temperature in Farenheit. Then, ask them to enter a character (C or K) to convert the temperature to Celsius or Kelvin, respectively. Print the converted temperature.

### Example Output
```
Enter a temperature in Farenheit: 32
Enter 'C' to convert to Celsius, or 'K' to convert to Kelvin: C
0.0
```

## ATMSimulator.java
* Write a program that simulates an ATM. The program should set the user's balance to a random value, and then display it. Then, it should ask them to enter a character to indicate if they want to make a deposit (d) or withdrawal (w), and then ask for an amount. The amount should be subtracted/added to the user's balance and the new balance should be displayed.

### Example output
```
Your balance is $503.
Would you like to deposit (d) or withdraw (w)? d
Please enter the amount: 100
Your new balance is $603.
```

## MultiplicationTable.java
* Write a program that asks the user for a number, and then prints the multiplication table for that number from 1 to 10.
* Hint: You can use a while loop to print out the multiplication table!

### Example Output
```
Enter a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

## AverageCalc.java
* Write a program that asks the user for a series of doubles. The program should stop when the user enters a negative number. Then, it should print the average of all the numbers.

### Example Output
```
Enter all of the numbers you'd like to average. Enter a negative number to stop.
100
20.5
3
-2

The average is: 41.6666
```

## Bonus: ATMSimulator.java Improvements
Make the following modifications:
* Allow the user to make multiple deposits and withdrawals. The program should stop when the user enters 'q' to quit.
* Prevent the user from making withdrawals that would result in a negative balance.
* After every 5 transactions, the user should receive interest on their current balance at a randomly chosen rate between 1 and 3%.
* Keep track of and display a second balance for the user's savings account, which should start at 0. The user should be able to enter 't' and then a number to transfer money from their main account to their savings account. The user should not be able to transfer more money than they have in their main account.
