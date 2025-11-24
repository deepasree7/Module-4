# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY
# AIM
To write a Python program to print the size of a dictionary using getsizeof() from the sys module.

# ALGORITHM
1. Begin the program.
2. Import the sys module to use the getsizeof() function.
3. Define the dictionaries with key-value pairs (dic1, dic2, dic3).
4. Use sys.getsizeof() to calculate the memory size of each dictionary.
5. Print the size of each dictionary in bytes.
6. Terminate the program.
# PROGRAM
```
import sys

dic1 = {"A": 1, "B": 2, "C": 3} 
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print("Size of dic1: {}bytes".format(sys.getsizeof(dic1)))
print("Size of dic2: {}bytes".format(sys.getsizeof(dic2)))
print("Size of dic3: {}bytes".format(sys.getsizeof(dic3)))
```

# OUTPUT

<img width="799" height="217" alt="image_24" src="https://github.com/user-attachments/assets/0b45a261-18b0-4817-8ca8-fd5d3d02abd2" />


# RESULT
Thus the Python program to print the size of a dictionary using getsizeof() from the sys module is executed successfully.
