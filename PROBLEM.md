•  Task 01 : Implement an algorithm for determining if an Nth is a divisor of an n Number (i.e. 2 is a divisor of 6). If so, determine if it’s an even number or odd number as well.
•  Solution: 
1.	In order to check if n can be divided by N and give zero remainder,we will proceed with an IF statement as following:

IF n % N == 0:
  THEN
  N is a divisor of n

2.	We will again employ if and else case statements to check 

// This means that remainder is zero on division

IF N % 2 == 0: 
  THEN
  N is an even number

ELSE:
  N is an odd number

3.	// Output – Possible Outcomes
EITHER print(“N is a divisor of:” ,n)
EITHER print(“N is an even number”)
EITHER print(“N is an odd number”)
