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
```Python
# Register No : 212225230159
# Developed By : MADHUMITHRA.P
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

```



# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

```



# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
<br><img width="1236" height="806" alt="Screenshot 2026-02-12 134420" src="https://github.com/user-attachments/assets/d08aab8f-9d95-4709-a369-f3644d8697e1" />
<br><img width="1261" height="372" alt="Screenshot 2026-02-12 134437" src="https://github.com/user-attachments/assets/7916d5e6-9d08-4360-ad0c-f0c3d72c364c" />


### 2-Norm of a Matrix
<br><img width="1240" height="828" alt="Screenshot 2026-02-12 134504" src="https://github.com/user-attachments/assets/d27cbbd8-cfc5-4286-b912-ca33cf0b72f4" />

<br><img width="1235" height="268" alt="Screenshot 2026-02-12 134529" src="https://github.com/user-attachments/assets/27c8a3a0-f9c6-45fb-8eb1-6f9ce02285bf" />

<br>

### Infinity Norm of a Matrix
<br><img width="1261" height="800" alt="Screenshot 2026-02-12 134546" src="https://github.com/user-attachments/assets/b7b40196-3e3e-4981-9abc-2c732b88ea98" />

<br><img width="1256" height="244" alt="Screenshot 2026-02-12 134602" src="https://github.com/user-attachments/assets/f497b8eb-a901-446f-920e-962416b20bb3" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
