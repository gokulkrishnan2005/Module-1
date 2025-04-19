## Experiment No: 4 – Conditional Statements- Divisible by 11

## AIM  
To Write a Python program to check whether the given number is divisblee by 11 using if..else statement
## ALGORITHM  
Input Step: Get the integer a from the user.

Check Divisibility:

Use the modulus operator (%) to check if a is divisible by 11. The modulus operation calculates the remainder of the division of a by 11.

If the remainder (a % 11) is equal to 0, then a is divisible by 11.

Output Step: Print the result based on the check:

If a % 11 == 0, print that a is divisible by 11.

Otherwise, print that a is not divisible by 11.
## PROGRAM
```python
# Reg.No-212223020008
# Name-Gokulkrishnan P


a=int(input())
if a%11==0:
    print('{} is divisible by 11'.format(a))
else:
    print("{} is NOT divisible by 11".format(a))
```

## OUTPUT
exp module1.png

## RESULT
Thus the given number is divisble by 11
