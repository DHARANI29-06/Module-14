# Exp.No:38  
## Deque - DELETION
### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.
### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  
### PROGRAM  
```
import collections
a=input()
b=input()
c=input()
de=collections.deque([a,b,c])
de.appendleft('h')
de.appendleft('o')
de.appendleft('n')
print("The deque after appending at right is :")
print(de)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/fc714ed4-6147-4d25-8caa-e589fa9aea75)
### RESULT
Thus , a Python program to delete elements at FRONT END of deque using a collection built-in function are verified.
