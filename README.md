# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
~~

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Define the matrix from the image
# Rows: [1, 1, 2], [-1, 1, 1], [2, 1, 1]
A = np.array([
    [2, 1, 1],
    [1, 1, 1],
    [1, -1, 2]
])

# Calculate the inverse
try:
    inverse_A = np.linalg.inv(A)
    
    # Print the result to match your expected format
    print(inverse_A)
    
except np.linalg.LinAlgError:
    print("Matrix is singular and cannot be inverted.")

    ~~~
## Output:
<img width="1264" height="847" alt="Screenshot 2026-03-24 154744" src="https://github.com/user-attachments/assets/80859e83-e97d-4f9a-a739-cb4789f17d40" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

