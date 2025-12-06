# Python Practice Programs: Factorial Calculation & Math Operations

## Task 1: Factorial Calculation Using a Function

### Objective

Develop a Python program that:

* Defines a function `factorial()` to calculate the factorial of a given number using iteration.
* Accepts user input.
* Displays the calculated factorial as output.

### Sample Run

Enter a number: 5
Factorial of 5 is: 120

### Program

```
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

num = int(input("Enter a number: "))
print("Factorial of", num, "is:", factorial(num))
```

---

## Task 2: Mathematical Operations Using the `math` Module

### Objective

Create a Python program that:

* Takes a numerical input from the user.
* Calculates the following using the `math` module:

  * Square root
  * Natural logarithm (base e)
  * Sine value (in radians)
* Displays the results clearly to the user.

### Sample Run

Enter a number: 10
Square root: 3.1622776601683795
Natural logarithm: 2.302585092994046
Sine: -0.5440211108893698

### Program

```
import math

num = float(input("Enter a number: "))

sqrt_value = math.sqrt(num)
log_value = math.log(num)
sin_value = math.sin(num)

print("Square root:", sqrt_value)
print("Natural logarithm:", log_value)
print("Sine:", sin_value)
```


## Running the Programs

```
python task1_factorial.py
python task2_math_operations.py
```

---

## Author

**Jashandeep Singh**

