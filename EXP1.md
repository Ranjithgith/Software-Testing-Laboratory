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
![Screenshot 2025-03-20 084353](https://github.com/user-attachments/assets/b16c4c9e-fc9a-4588-8904-00b31b13f954)

## 2.While..do:

![Screenshot 2025-03-20 084757](https://github.com/user-attachments/assets/2aceedbd-8756-47b3-b66c-085bafae74dd)

## 3.switch:
![Screenshot 2025-03-20 084908](https://github.com/user-attachments/assets/a9785faa-8522-45fe-949b-c66c470b29ea)

## 4.if..else:
![Screenshot 2025-03-20 085056](https://github.com/user-attachments/assets/dda4c812-43ec-4e54-9c72-98f6e8312f53)

 ## 5.for:


![Screenshot 2025-03-20 085150](https://github.com/user-attachments/assets/4b2a705c-9acb-4883-9396-92a829ed23b9)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


