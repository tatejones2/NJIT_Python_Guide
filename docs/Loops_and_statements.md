# Python Control Structures

This README explains three basic control structures in Python: **if statements**, **while loops**, and **for loops**.

---

## If Statements

An `if` statement allows your code to make decisions. It runs a block of code only if a condition is true.

```python
x = 10

if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
```

---

## While Loops

A `while` loop repeats as long as a condition remains true.

```python
count = 0

while count < 5:
    print("Count is:", count)
    count += 1
```

This will print numbers from 0 to 4. Be careful — if the condition never becomes false, the loop will run forever.

---

## For Loops

A `for` loop is used to iterate over a sequence (like a list, string, or range of numbers).

```python
for i in range(5):
    print("Iteration:", i)

'''
Output:
Iteration: 0
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4
'''
```

This will print numbers from 0 to 4.

You can also loop through items in a list:

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)

'''
apple
banana
cherry
'''
```

---

## Summary

* **`if` statements** → make decisions based on conditions.
* **`while` loops** → repeat code while a condition is true.
* **`for` loops** → iterate over a sequence of items.
