# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda x, y: x + y
result = f(a, b)

print("Sum:", result)
```

## Output

<img width="482" height="222" alt="image" src="https://github.com/user-attachments/assets/20bacc6a-994a-4947-a65b-c4d60c725d8b" />

## Result

Hence, the code is executed successfully, and the **lambda function** correctly computes and displays the sum of the two input numbers.
