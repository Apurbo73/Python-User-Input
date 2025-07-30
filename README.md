# Python User Input
In Python, you can get **user input** using the built-in `input()` function.

---

### ✅ **Basic Example**

```python
name = input("Enter your name: ")
print("Hello,", name)
```

* `input()` always returns a **string**.
* You can prompt the user with a message inside the parentheses.

---

### ✅ **Convert Input to Integer or Float**

```python
age = int(input("Enter your age: "))  # Converts to integer
height = float(input("Enter your height in meters: "))  # Converts to float
```

---

### ✅ **Example with Condition**

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

---

### ✅ **Multiple Inputs on One Line**

```python
x, y = input("Enter two numbers separated by space: ").split()
x = int(x)
y = int(y)
print("Sum:", x + y)
```

You can also use `map()` to convert directly:

```python
x, y = map(int, input("Enter two numbers: ").split())
```

---

