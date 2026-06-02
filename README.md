
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
num = 16
binary = bin(num)
print("Binary representation of", num, "is", binary)
```
## Output

<img width="525" height="135" alt="image" src="https://github.com/user-attachments/assets/ac0b7c5e-2922-4437-92a8-21425e679b53" />

## Result
The program was excecuted successfully and the result was obtained

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def find_modulo(a, b):
    return a % b
num1 = 17
num2 = 5
result = find_modulo(num1, num2)
print("Modulo is:", result)
```
## Output
<img width="325" height="110" alt="image" src="https://github.com/user-attachments/assets/137a93da-07d8-45b7-b1c7-ce87d2cf3cea" />

## Result
the program has been excecuted successfully and the result was obtained

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
add = lambda a, b: a + b
x = 10
y = 20
result = add(x, y)
print("Sum is:", result)
```
## Output
<img width="229" height="69" alt="image" src="https://github.com/user-attachments/assets/cd5a7eb4-8195-4ac7-a573-d6e3bc87322e" />

## Result
the program has been excecuted successfully and the result was obtained


# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
rows = 7
for i in range(rows):
    num = 1
    for j in range(rows - i - 1):
        print(" ", end="")

    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()
```
## Sample Output
<img width="411" height="309" alt="image" src="https://github.com/user-attachments/assets/a5f84f4e-caea-4e04-96b6-30cd388b9691" />

## Result
the program has been excecuted successfully and the result was obtained

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = 1221
original = num
reverse = 0
while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10
if original == reverse:
    print(original, "is a Palindrome")
else:
    print(original, "is not a Palindrome")
```
## Output
<img width="283" height="110" alt="image" src="https://github.com/user-attachments/assets/fb477360-978c-4606-bf38-0e849ce155fd" />

## Result
program has been excecuted successfully and the result was obtained
