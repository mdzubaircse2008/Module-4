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
dict1={'key1': 1, 'key2': 2, 'key3': 3}
dict2={'key1': 4, 'key2': 5}
def merge():
    merged={**dict1, **dict2}
    print(merged)
merge()
```

## Output
![alt text](m42.png)
## Result
Hence the program executed and the output is verified