# PYTHON Cheatsheet

```python
value = 1
value is None

list = []
list[index]
list.append(value)
list.remove(value)

for item in list:
    print(item)

for i, item in enumerate(list):
    print(i, item)

dictionary = {}
dictionary[key] || dictionary.get(key, None)
dictionary[key] = value
key in dictionary
value in dictionary.values()

for key, value in dictionary.items():
    print("{}, {}").format(key, value) || print(f"{key}, {value}")

if 1 == 1:
    foo = "bar"
elif 2 == 2:
    bar = "foo"
else:
    foobar = "barfoo"

for index in range(0, len(string)):
    print(string[index])

def name(arg1, arg2):
    return arg1 + arg2

# memoization
memo = {}
if key not in memo:
    memo[key] = value
return memo[key]
```
