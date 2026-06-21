# loops-using-python-in-internship-4
# Documentation: Looping Statements in Python

## Objective

This program demonstrates the two primary looping constructs in Python:

* `for` loop
* `while` loop

Loops are used to execute a block of code repeatedly based on a sequence or a condition.

## Program Code

### Using a `for` Loop

```python
a = [1, 2, 3, 4, 5]

for i in a:
    print(i)
```

### Intended `while` Loop Example

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

## Explanation

### 1. `for` Loop

```python
a = [1, 2, 3, 4, 5]

for i in a:
    print(i)
```

* A list `a` containing the numbers `1` through `5` is created.
* The `for` loop iterates through each element in the list.
* During each iteration, the current value is stored in the variable `i` and printed.

**Output:**

```
1
2
3
4
5
```

### 2. `while` Loop

A `while` loop repeatedly executes a block of code as long as its condition evaluates to `True`.

Example:

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

**Output:**

```
1
2
3
4
5
```

The variable `count` starts at `1` and increases by `1` after each iteration until it becomes greater than `5`.

## Error in the Original Code

The original code was:

```python
while Python:
    True
```

This is incorrect because:

1. `Python` is treated as a variable but has not been defined, resulting in a `NameError`.
2. The statement `True` by itself does nothing and does not produce any output or change the loop condition.

If an infinite loop is intended, it should be written as:

```python
while True:
    print("This loop runs forever until interrupted.")
```

However, such loops should include a `break` statement or another exit condition to avoid running indefinitely.

## Key Concepts

* **`for` loop:** Iterates over elements in a sequence such as a list, tuple, or string.
* **`while` loop:** Repeats execution as long as a specified condition remains `True`.
* **Loop variable:** Holds the current value during each iteration.
* **Termination condition:** Determines when a loop should stop.

## Conclusion

`for` loops are best suited for iterating over collections or known sequences, while `while` loops are useful when repetition depends on a condition rather than a fixed number of iterations. Understanding both is fundamental to writing efficient Python programs.
