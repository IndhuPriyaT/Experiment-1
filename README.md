# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
## 1. do...while
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
## 2. while...do
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```

## 3.if-else
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
```

## 4. while
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```

## 5.for
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## Output
## 1. do...while

<img width="791" height="146" alt="image" src="https://github.com/user-attachments/assets/0a5daa66-a4d4-4222-8fa6-72a7e703443c" />

## 2. while...do
<img width="640" height="203" alt="image" src="https://github.com/user-attachments/assets/ab011647-1bff-4615-83b7-bd07044d275f" />

## if-else
<img width="338" height="123" alt="image" src="https://github.com/user-attachments/assets/bc899a30-edf7-43ba-b17e-d7013cabd27c" />

## switch

<img width="302" height="90" alt="image" src="https://github.com/user-attachments/assets/285441a2-bf15-4a9e-9b2a-f83b0ce68418" />


## for
<img width="329" height="126" alt="image" src="https://github.com/user-attachments/assets/d67e6058-9894-4688-b138-48c111ba712d" />


## Result

Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


