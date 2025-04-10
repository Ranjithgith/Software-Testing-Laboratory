# Ex.No: 2   Matrix Multiplication 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:
```
num = input("Enter a positive number: ")
if num.isnumeric():  
    z = int(num)
    if z < 2:
        print("Not a Prime Number")  
    elif z == 2:
        print("Prime Number")  
    else:
        flag = 1  
        for i in range(2, z // 2 + 1):
            if z % i == 0:
                flag = 0  
                break
        
        if flag == 1:
            print("Prime Number")
        else:
            print("Not a Prime Number")
else:
    print("Enter a valid positive number")
```












### Output:


[exp2 stl.pdf](https://github.com/user-attachments/files/19677456/exp2.stl.pdf)




### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

