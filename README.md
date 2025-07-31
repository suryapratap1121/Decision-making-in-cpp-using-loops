Implementing-CPP-decision-making-statements-Loop
Aim: Implementation of loops in C++

Software: Mingw CPP compiler, VS code , Online C/C++ compiler

#Program 1 Even number

The program simply prints even numbers from 1 to 10. It goes through each number one by one and checks if it can be divided by 2 without any leftovers. If yes, it's called an even number and gets printed. It's a basic way to learn how loops and conditions work in coding.

#program 2 "SIT" using loops

Algorithm:

Initialize a loop control variable (e.g., int i = 0)
Check Condition (e.g., i < 5)
If true, proceed to the loop body
If false, exit the loop
Execute the loop body
Increment/Update the control variable (e.g., i++)
Repeat from step 2
This program uses a for loop to print the word “SIT” five times, each time with a number in front of it, like “1.SIT”, “2.SIT”, and so on. The loop starts at 0 and runs while i is less than 5. Inside the loop, i+1 is used so the numbering starts from 1 instead of 0. It’s a simple way to understand how loops work and how to combine text with numbers in output.

#Program 3 Use of continue in loops

The continue statement in C++ is used inside loops to skip the current iteration and move directly to the next one. When the program hits continue, it ignores any code that comes after it in the loop for that specific cycle. It's helpful for filtering out values or conditions you want to avoid without breaking the loop completely. This program prints odd numbers from 1 to 9 using a for loop and the continue statement. The loop runs from 1 to 9, and for each number, it checks whether the number is even using i % 2 == 0. If the number is even, continue skips the rest of the loop for that iteration. If the number is odd, it prints the number. This is a basic way to understand how skipping specific values in a loop works using conditions.

#Program 4 STAR pattern-1

This program uses nested loops to print a triangular star pattern. The outer loop runs from 1 to 6, controlling the number of rows. For each row, the inner loop prints stars equal to the row number. After printing stars in each row, a newline character is added to start a new row.

Algorithm: Star Pattern 1.Start 2.Initialize outer loop variable i to 1 3.Repeat while i is less than or equal to 6: 4.Initialize inner loop variable j to 1 5.Repeat while j is less than or equal to i: 6.Print "* " (a star followed by a space) 7.Increment j by 1 8.Print a newline to move to the next row 9.Increment i by 1 10.End

#Program 5 STAR pattern-2

Algorithm:

Start
Set the number of rows to 6
Initialize loop variable i to 6
Repeat while i ≥ 1:
Initialize j to 1
Repeat while j ≤ i:
Print * (a star followed by a space)
Increment j by 1
Print newline to move to the next row
Decrement i by 1
End
#Program 6 STAR pattern-3

Algorithm:

Start
Set total number of rows as 6
Initialize outer loop variable i to 1
Repeat while i ≤ 6:
Initialize space counter j to 1
Repeat while j ≤ (6 − i):
Print two spaces " " for alignment
Increment j by 1
Initialize star counter k to 1
Repeat while k ≤ i:
Print "* " (a star and space)
Increment k by 1
Print newline to move to next row
Increment i by 1
End
#Program 7 STAR pattern-4

Algorithm:

Start
Set the number of rows to 6
Initialize outer loop variable i to 6
Repeat while i ≥ 1:
Initialize space counter j to 0
Repeat while j ≤ i:
Print a space " " for indentation
Increment j by 1
Initialize star counter k to 6 10.Repeat while k ≥ i:
Print " *" (a space and a star for alignment)
Decrement k by 1
Print newline to move to the next row
Decrement i by 1
END
#Program 8 Number pattern

This program prints a number triangle using nested for loops and a counter variable. It starts with a = 1 and increases a with each printed value. The outer loop controls the rows, running from 0 to 3. The inner loop prints numbers in each row, starting with one number in the first row and increasing by one in each subsequent row. The pattern is formed by incrementing a using a++ for every printed number, creating a neat triangle of numbers from 1 to 10.

#Program 9 Printing 1-20

This program uses a for loop to print numbers from 1 to 20, with each number on a separate line. The loop starts with i = 1 and continues until i <= 20, incrementing i by 1 in each iteration. Inside the loop, cout << i displays the current value of i, and cout << endl moves to the next line after printing each number.

#Program 10 Authenticate the password

This program demonstrates the use of a while loop to create a basic password validation system. It defines a fixed password "007" and continually prompts the user to input a password using cin. The loop runs indefinitely due to while(true) until the user inputs a string that matches the preset password. If the input is correct, the program displays "correct!!" and exits the loop using break; otherwise, it prints "try again" and repeats.

Algorithm:

Start
Store the correct password (e.g., "007")
Begin an infinite loop using while(true)
Prompt the user to enter a password
Read user input and store it in a variable
Check if the input matches the stored password:
If yes: Print "correct!!"
Exit the loop using break
If no: Print "try again"
Repeat the loop
End
Conclusion: We have learnt the concepts of looping in C++ and also used conditions in it for implementing a suitable program.
