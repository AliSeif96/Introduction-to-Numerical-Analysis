## session 2 (Exercises Series 1)
____________________________________
### 1.Calculate the Area of a Triangle
`Commenting is required for all lines of code. (Explain each comment line in both programming and conceptual terms. An example is provided.)`

#### Problem Statement:
Given that `a`, `b`, and `c` are the sides of a triangle:
- `a` is fixed at 5.
- `b` is fixed at 6.1.
- `c` is entered by the user (7).

#### Formulas to Calculate the Area:

Formula for the semi-perimeter:$$ s = (a + b + c) / 2 $$

Formula for the area of the triangle:$$ area = (s * (s - a) * (s - b) * (s - c)) ** 0.5 $$


What does this part of the code `'%0.2f'` % do? (Be sure to comment on its functionality)



###### To understand this example, you should have the knowledge of the following Python programming topics:
<ul>
    <li style="font-size: 10px;">0. Python Basic Output</li>
    <li style="font-size: 10px;">1. Variables and Data Types</li>
    <li style="font-size: 10px;">2. Taking Input from the User</li>
</ul>


```python
# Python Program to find the area of triangle

# Variables
a = 5 #An int variable (representing one of the sides of the triangle)
...

# Uncomment below to take inputs from the user
...

# calculate the semi-perimeter
...

# calculate the area
...

print('The area of the triangle is %0.2f' %area) #...
```
____________________________________
### 2.Even or Odd Checker with Exit Condition
`Commenting is required for all lines of code.`

#### Problem Statement:
Write a Python program that continuously accepts numbers from the user and determines whether the entered number is `even` or `odd`. The program should stop running when the user inputs `0`. (This means that it will always run until the number zero is entered)

Your program should:

1.Prompt the user to enter an integer.

2.If the number is:
-  `0`, display a message indicating the program is exiting and terminate the loop.
-  `Even`, display the message <number> is Even.
-  `Odd`, display the message <number> is Odd.

3.Repeat this process until the user enters 0.


###### To understand this example, you should have the knowledge of the following Python programming topics:
<ul>
    <li style="font-size: 10px;">0. Python Basic Output</li>
    <li style="font-size: 10px;">1. Variables and Data Types</li>
    <li style="font-size: 10px;">2. Taking Input from the User</li>
    <li style="font-size: 10px;">3. Conditionals</li>
    <li style="font-size: 10px;">4. Loops</li>
</ul>

```python
# Even or Odd Checker with Exit Condition

...
```

____________________________________
### 3.Recursive Factorial Calculator
`Commenting is required for all lines of code.`

Write a program to calculate the factorial of a number using recursion. Your program should:

1.Define a recursive function `factorial(x)` that:
-  Returns `1` if the input is `0` or `1` (base case).
-  Otherwise, calculates the factorial by calling itself with `x - 1`.

2.Prompt the user to input a non-negative integer.

3.Call the factorial function with the user's input.

4.Print the factorial of the number.


###### To understand this example, you should have the knowledge of the following Python programming topics:
<ul>
    <li style="font-size: 10px;">0. Python Basic Output</li>
    <li style="font-size: 10px;">1. Variables and Data Types</li>
    <li style="font-size: 10px;">2. Taking Input from the User</li>
    <li style="font-size: 10px;">3. Conditionals</li>
    <li style="font-size: 10px;">5. Functions</li>
</ul>


```python
# Python program to find the factorial of a number provided by the user
# using recursion

def factorial(x):
    """This is a recursive function
    to find the factorial of an integer"""

    if ...:
        return 1
    else:
        # recursive call to the function
        return (...)


# to take input from the user (must num is int)
num = int(...)

# call the factorial function
result = factorial(num)

print("The factorial of", num, "is", result)

```


