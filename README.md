# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Import the numpy module to use the built-in functions for calculation

### Step 2: Using the scipy.linalg import , we can find the solutions

### Step 3: Get input from users

### Step 4: End the program

## Program:
(i) To find the L and U matrix

                                            
                                            Developed by: SADHANA SHREE B
                                            RegisterNumber: 212223230177
                                        
                                            import numpy as np
                                            from scipy.linalg import lu
                                            A=np.array(eval(input()))
                                            P,L,U = lu(A)
                                            print(L)
                                            print(U)

                                      
(ii) To find the LU Decomposition of a matrix
                                          
                                           Developed by: SADHANA SHREE B
                                           RegisterNumber: 212223230177
                                          
                                           import numpy as np
                                           from scipy.linalg import lu_factor, lu_solve
                                           A=np.array(eval(input()))
                                           b=np.array(eval(input()))
                                           lu,piv=lu_factor(A)
                                           x=lu_solve((lu,piv),b)
                                           print(x)


## Output:
(i) To find the L and U matrix
![Screenshot 2024-04-17 141523](https://github.com/SadhanaShreee/LU-Decomposition/assets/144517664/071c11a5-3771-4f55-82da-69b0c48e32fd)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-17 141553](https://github.com/SadhanaShreee/LU-Decomposition/assets/144517664/2d8c0d59-481a-4280-aa48-b1d751eda229)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

