# Exp.No:18  
## FILES - FREQUENCY OF CHARACTERS IN A FILE
# AIM
To write a Python program that reads a file and counts the frequency of each character in it.

# ALGORITHM
1. Begin the program.
2. Define the function create_file() that accepts two arguments:
file_path: The path to the file.
content: The string content to be written into the file.
3. Open the file specified by file_path in write mode ('w'), and write the provided content into the file.
4. Close the file (this is automatically done when exiting the with block).
5. Define the function character_frequency() that accepts one argument:
  file_path: The path to the file whose character frequency is to be calculated.
6. Open the file specified by file_path in read mode ('r'), and read its content into the variable content.
7. Initialize an empty dictionary (d1) to store the frequency of each character using defaultdict(int).
8. Loop through each character in the content:
For each character ch, increment its corresponding frequency in the dictionary d1.
9. Return the dictionary d1, which contains the frequency of each character in the file.
10. Terminate the program.
# PROGRAM
```
from collections import defaultdict
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def char_frequency(file_path):
    with open(file_path,'r') as f1:
        content=f1.read()
    d1=defaultdict(int)
    for ch in content:
        d1[ch]+=1
    return d1
```
# OUTPUT
<img width="804" height="259" alt="image" src="https://github.com/user-attachments/assets/fc8a4efd-6e10-40cc-bf1e-4cd036444df9" />

<img width="800" height="265" alt="image" src="https://github.com/user-attachments/assets/b7e10535-ad04-443c-9dad-675b7274e2c1" />

<img width="802" height="260" alt="image" src="https://github.com/user-attachments/assets/09a4d5ee-5fc5-4039-bc52-099fd47fb878" />

<img width="805" height="259" alt="image" src="https://github.com/user-attachments/assets/68aafce1-b73a-4ab3-af83-83d7fe5071b6" />


# RESULT
Thus the Python program that reads a file and counts the frequency of each character in it is executed successfully.
