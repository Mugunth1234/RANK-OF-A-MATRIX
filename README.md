# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equation and assign in np.array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end the program
## Program:
import numpy as np
def find_rank(matrix):
    A = np.array(matrix)
    rank = np.linalg.matrix_rank(A)  
    return rank
matrix = [[3, 2, 5], [1, 1, 2], [3, 3, 6]]
rank = find_rank(matrix)
print(rank)
## Output:
![Screenshot 2024-11-27 202109](https://github.com/user-attachments/assets/b6732b68-2d0a-4d6d-8db4-2f2a2b1fb1e2)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

