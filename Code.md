# Ques.1 
Make a function sum which takes two numbers as input and print the sum inside
the function.

#solution
``` python
def sum():
    a=int(input("Enter first number:"))
    b=int(input("Enter second number:"))
    print("Sum:",a+b)
sum()
```
Testcase 1: \
Enter first number: 5\
Enter second number: 3\
Sum: 8

Testcase 2:\
Enter first number: 12\
Enter second number: 9\
Sum: 21

Testcase 3:\
Enter first number: 10\
Enter second number: 10\
Sum: 20

# Ques.2
Make a function avg which takes four numbers as input and print the average of the numbers
inside the function.

#solution
``` python
def avg():
    a=int(input("Enter first number:"))
    b=int(input("Enter second number:"))
    c=int(input("Enter third number:"))
    d=int(input("Enter fourth number:"))
    print("Average:",(a+b+c+d)/4)
avg()
```
Testcase 1: \
Enter first number: 5\
Enter second number: 6\
Enter third number: 7\
Enter fourth number: 2\
Average: 5

Testcase 2:\
Enter first number: 8\
Enter second number: 10\
Enter third number: 3\
Enter fourth number: 9\
Average: 7.5

Testcase 3:\
Enter first number: 1\
Enter second number: 9\
Enter third number: 21\
Enter fourth number: 12\
Average: 10.75