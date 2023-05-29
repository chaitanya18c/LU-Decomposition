# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scripy package import lu_factor() and lu_solve().
3. Get two inputs from user and pass it as matrix array.
4. Find lu and pivot value of first matrix using lu_factor().and Find solution of the matrix by using lu_solve() by passing lu,pivot values as first argument and second matrix as second argument.

## Program:
(i) To find the L and U matrix

    '''Program to find L and U matrix using LU decomposition.
    Developed by:CHAITANYA P S
    RegisterNumber:212222230024 
    '''
    import numpy as np
    from scipy.linalg import lu
    A = np.array(eval(input()))
    P,L,U=lu(A)
    print(L)
    print(U)

(ii) To find the LU Decomposition of a matrix

     '''Program to solve a matrix using LU decomposition.
    Developed by: CHAITANYA P S
    RegisterNumber: 212222230024
    '''
    # To print X matrix (solution to the equations)
    import numpy as np
    from scipy.linalg import lu
    A = np.array(eval(input()))
    B = np.array(eval(input()))
    C = np.linalg.solve(A,B)
    print(C)

## Output:
![lu decomposition](https://github.com/chaitanya18c/LU-Decomposition/assets/119392724/27207ecb-4af5-4979-b363-f3d5a882a31a)

![lu decomposition](https://github.com/chaitanya18c/LU-Decomposition/assets/119392724/7777117c-484f-4811-aaa7-6f1f30b1ceb3)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

