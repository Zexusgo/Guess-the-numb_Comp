# Guess the number game

**Status**: Completed 

## Description
A simple guess the number game where Python program generates a random number and player tries to guess it.

## Notes
- import the random module
- define a function
- randint(a,b) range of ab
- Initial guess so that it's not between the range
- Using while loop because we don't have predefined numbers to iterate over
- With if statement create structure where it returns whether input is higher or lower.

## How does it works?
- By changing the value from the program in the braces of fun(), you decide the upper limit.
- On running the program, it ask's the user for input
- Depending on input, it will display either of five message's
  1. "Number is greater"
  2. "Number is smaller"
  3. "Please! enter a number between 1 and (the number edited, default: 10)"
  4. "Congratulations! Your number (number entered by user) is correct"
  5. "Please! Enter a number." in case, if the input isn't a number
- In case of first four message, the program will ask for reinput from user and repeat of steps until you get a correct number.
      
## Features
Program genrates the number with Random library

## Acknowledgement
Thanks for the tutorial [Freecodecamp](https://www.youtube.com/watch?v=8ext9G7xspg&t=443s)
