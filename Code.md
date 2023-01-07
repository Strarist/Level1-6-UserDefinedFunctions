# Question 1:
Make a function sum() which takes two numbers as input and print the sum inside
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
Input:
>Enter first number: 5\
>Enter second number: 3 

Output:
> Sum: 8

Testcase 2:\
Input:
>Enter first number: 12\
>Enter second number: 9

Output:
> Sum: 21

Testcase 3:\
Input:
>Enter first number: 10\
>Enter second number: 10

Output:
> Sum: 20

# Question 2:
Make a function avg() which takes four numbers as input and print the average of the numbers
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
Input:
>Enter first number: 5\
Enter second number: 6\
Enter third number: 7\
Enter fourth number: 2

Output:
>Average: 5

Testcase 2:\
Input:
>Enter first number: 8\
Enter second number: 10\
Enter third number: 3\
Enter fourth number: 9

Output:
>Average: 7.5

Testcase 3:\
Input:
>Enter first number: 1\
Enter second number: 9\
Enter third number: 21\
Enter fourth number: 12

Output:
>Average: 10.75

# Question 3:
Make a function reverse() and take a word as input
and print it after reversing it inside the function.

#solution
``` python
def reverse():
    a=input("Enter the word: ")
    print(a[::-1])
reverse()
```
Testcase 1:\
Input:
>Enter the word: Arist

Output:
>tsirA

Testcase 2:\
Input:
>Enter the word: Bennett

Output:
>ttenneB

Testcase 3:\
Input:
>Enter the word: Srivalli

Output:
>illavirS

# Question 4:
Make a function maximum() and take three numbers from user
as input and find the maximum number out of the three.

``` python
def maxim():
    a=int(input("Enter first number: "))
    b=int(input("Enter second number: "))
    c=int(input("Enter third number: "))
    print("Maximum number is:",max(a,b,c))
maxim()
```
Testcase 1:\
Input:
>Enter first number: 4\
Enter second number: 7\
Enter third number: 32

Output:
>Maximum number is: 32

Testcase 2:\
Input:
>Enter first number: 4\
Enter second number: 4\
Enter third number: 4

Output:
>Maximum number is: 4

Testcase 3:\
Input:
>Enter first number: 6\
Enter second number: 12\
Enter third number: 26

Output:
>Maximum number is: 26

# Question 5:
Make a function fact() and take a number as input from user
and return factorial of that number and print it outside
the function.(Don't use in-built function).

``` python
def fact():
    n=int(input('Enter the number: '))
    f=1
    for i in range(1,n+1):
        f*=i
    return f
factorial=fact()
print('Factorial:',factorial)
```
Testcase 1:\
Input:
>Enter the number: 5

Output:
>Factorial: 120

Testcase 2:\
Input:
>Enter the number: 6

Output:
>Factorial: 720

Testcase 3:\
Input:
>Enter the number: 3

Output:
>Factorial: 6

# Question 6:
Make a function prime() and take a number as input from
the user and check whether it is prime or not.

``` python
def prime():
    num=int(input("Enter the number: "))
    c=0
    for i in range(2,num):
        if num%i==0:
            c+=1
    if c==0:
        print('Prime')
    else:
        print('Non-prime')
prime()
```
Testcase 1:\
Input:
>Enter the number: 8

Output:
>Non-prime

Testcase 2:\
Input:
>Enter the number: 127

Ouput:
>Prime

Testcase 3:\
Input:
>Enter the number: 19

Output:
>Prime

# Question 7:
Make a function primebtw() and take the starting number and ending number
as input from user and print the prime numbers between them inclusive of the boundary
numbers. Example: a<= primebtw <=b
``` python
def prime():
    num1=int(input("Enter the starting number: "))
    num2=int(input("Enter the ending number: "))
    for k in range(num1,num2+1):
        c=0
        for i in range(2,k):
            if k%i==0:
                c+=1
        if c==0:
            print(k)
prime()
```
Testcase 1:
Input:
>Enter the starting number: 2\
Enter the ending number: 10

Output:
>2\
3\
5\
7

Testcase 2:
Input:
>Enter the starting number: 11\
Enter the ending number: 13

Output:
>11\
13

Testcase 3:
Input:
>Enter the starting number: 7\
Enter the ending number: 20

Output:
>7\
11\
13\
17\
19