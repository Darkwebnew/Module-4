# Module 4

---

# Experiment 1: Classes and Objects in Python - Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi * r²
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```python
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")
r = float(input())
obj = cse()
obj.mech(r)
```

## Output
<img width="1184" height="298" alt="{0BC23070-C7EE-444E-826E-A9AAB5AB1728}" src="https://github.com/user-attachments/assets/342c75b4-bae9-4f4e-85d1-a53df94fd231" />

## Result
Thus the program executed successfully.

---

# Experiment 2: Dictionary Operations in Python - Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
<img width="1199" height="365" alt="{67DB3DA4-4F6D-4FC3-BDDB-0EB820A082DF}" src="https://github.com/user-attachments/assets/d4d4c622-356a-4ff5-aff5-60eb06ff9fe2" />

## Result
Thus the program executed successfully.

---

# Experiment 3: Dictionary - Python Program to Sort a Dictionary by Keys and Values

## 🎯 Aim
To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

## 🧠 Algorithm
1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

## 🧪 Program
```python
data=eval(input())
sort=dict(sorted(data.items()))
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sort.items():
    print(f"({key}, {value}) ",end="")
```

## Sample Output
<img width="1264" height="116" alt="{8EC966A5-3C2D-4E98-BCC2-56232F6239E0}" src="https://github.com/user-attachments/assets/a6f67ef2-e0b2-4711-b66f-d57c1390e02f" />

## Result
Thus, the program has been successfully executed.

---

# Experiment 4: Exception Handling in Python - Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```python
list1=[5, 10, 20] 
try: 
   print(list1[5]) 
except: 
   print("You're out of list range")
```

## Output
<img width="725" height="173" alt="{5CFD2AAD-719C-4C51-90EF-92DF73C994A7}" src="https://github.com/user-attachments/assets/e5c09a1b-2ff7-4320-94af-20bf087fe2ad" />

## Result
Thus, the program has been successfully executed.

---

# Experiment 5: File Handling in Python - Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```python
file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines[0] not in 'T': 
      count+=1 
print(count)
```

## Output
<img width="450" height="83" alt="image" src="https://github.com/user-attachments/assets/e233bd1b-36ef-40a2-b459-a7c2385591ea" />

## Result
Thus the program executed successfully.
