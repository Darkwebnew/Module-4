## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
<img width="1199" height="365" alt="{67DB3DA4-4F6D-4FC3-BDDB-0EB820A082DF}" src="https://github.com/user-attachments/assets/d4d4c622-356a-4ff5-aff5-60eb06ff9fe2" />


## Result
Result Thus the program executed successfully.
