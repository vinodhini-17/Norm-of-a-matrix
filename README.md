# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
``````
# Register No:23013556
# Developed By:vinodhini.k

``````
# 1-Norm of a Matrix
``````
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

``````

# 2-Norm of a Matrix
``````
import numpy as np
array1=([[1,2],[3,4],[1,7]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
``````


# Infinity Norm of a Matrix
``````
import numpy as np
array1=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
``````



## Output:
### 1-Norm of a Matrix
![norm 1 out](https://github.com/vinodhini-17/Norm-of-a-matrix/assets/145742741/14c15dea-c24e-411a-8ab5-b689bbced2ff)

### 2-Norm of a Matrix
![norm 2 out](https://github.com/vinodhini-17/Norm-of-a-matrix/assets/145742741/70cb5046-bf50-4a8e-a308-7cd3f65341e3)

### Infinity Norm of a Matrix
![norm3  out](https://github.com/vinodhini-17/Norm-of-a-matrix/assets/145742741/d5f9e74c-6f1c-4faa-9230-d4bd30ae220d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
