# **Printing Statements**

The printing statement in the python is `print()`. It can be used to display values or output messages.

<hr>

## **Examples**

###  **Example 1: Print a single value**

```py
print("Hello World!)
```
**Output**: Hello World!

### **Example 2: Printing Variables**

```py
x = 10
y = 20
print("The value of x is:", x)
print("The value of y is:", y)
```
**Output**: 
The value of x is: 10
The value of y is: 20

### **Example 3: Printing multiple variables using f-strings (Python 3.6+)**

```py
name = "Alex"
age = 30
print(f"My name is {name} and I am {age} years old.")
```
**Output**: My name is Alex and I am 30 years old.

**Note:**  *f-string formatting is more efficient.*

### **Example 4: Using .format method for string formatting**

```py
name = "Alex"
age = 30
print("My name is {} and I am {} years old.".format(name,age))
```
**Output**: My name is Alex and I am 30 years old.

**Note:** *This method can take multiple arguments but it's not as readable or efficient as the newer f-string formatting.*

<hr>
