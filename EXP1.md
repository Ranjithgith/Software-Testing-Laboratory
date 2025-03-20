# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:20/03/25                                                                    
### REGISTER NUMBER :212224240131 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### 1.Do...While
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end='') 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display()

```
### 2.While...Do
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric(): 
    start=int(start) 
    end=int(end) 
    while start<end: 
        print(start) 
        start+=1 
else:
    print("Enter a valid positive number.")

```
### 3.Switch
```
def switch(): 
    switcher={ 
    0:"even", 
        1:"odd" 
    } 
    n=input('Enter a value for N: ')
    try: 
        n=int(n) 
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.")
switch()

```
### 4.If...Else
```
def compare(): 
    a=input("Enter a value for A: ") 
    b=input("Enter a value for B: ") 
    try: 
        a=int(a) 
        b=int(b) 
        if a>b: 
            print("A is greater than") 
        elif a<b: 
            print("B is greater than") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")
compare()

```
### 5.For
```
def iterate(): 
    string=input("Enter a string: ")
    for i in string: 
        print(ord(i),end=" ")
iterate()

```
### Output:
## 1.do..while:
![Screenshot 2025-03-13 083535](https://github.com/user-attachments/assets/78bf7c0e-78d2-4363-9539-294a1b1c78ab)
## 2.While..do:

![Screenshot 2025-03-13 084004](https://github.com/user-attachments/assets/980721da-3964-4354-a6a4-b1169fb9361b)
## 3.switch:

![Screenshot 2025-03-13 084332](https://github.com/user-attachments/assets/49a0c523-27ef-4789-9917-c3fbde05c9b0)

## 4.if..else:
![Screenshot 2025-03-13 084607](https://github.com/user-attachments/assets/7a1f2f2f-b761-4537-80f6-77dd5cf1211d)
 ## 5.for:
 ![Screenshot 2025-03-13 085011](https://github.com/user-attachments/assets/52361184-0521-4a6d-9e8a-29fb73ff4e2a)




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


