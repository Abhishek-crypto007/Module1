# Ex 1: Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```python3
n=int(input())
if n%2==0:
   print("Even")
else:
   print("Odd")

```

## Output
<img width="467" height="373" alt="image" src="https://github.com/user-attachments/assets/ed812c83-e221-499a-a470-f1c81e21b087" />

## Result
Thus the python program to check whether the given number is **even** or **odd** using `if...else` statements is completed successfully.



<br>
<br>



# Ex 2: Datatypes - Accessing String Characters in Python

## 🎯 Aim
To write a Python program to get a string value from the user and access specific string characters using indexing and slicing.

## 🧠 Algorithm
1. Read a string from the user using `input()`.
2. Display the entire string.
3. Access and display:
   - The first character (`str[0]`)
   - The last character (`str[-1]`)
   - A substring from index 1 to 4 (`str[1:5]`)
   - A substring from index 5 to 6 (`str[5:7]`)

## 🧾 Program
```python
s = input("Enter a string: ")

print("str = ", s)
print("str[0] = ", s[0])
print("str[-1] = ", s[-1])
print("str[1:5] = ", s[1:5])
print("str[5:7] = ", s[5:7])
```

## OUTPUT
<img width="1546" height="827" alt="image" src="https://github.com/user-attachments/assets/ca20c29f-f7ea-43e1-aa56-4971684fc1aa" />

## ✅ Result
Thus, the program has been successfully executed to read a string and access its characters using indexing and slicing.


<br>
<br>

# Ex 3:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```python3
a = (11 == True)
b = (5==False)
c = True+54
d = False+7
print('a is',a)
print('b is',b)
print('c:',c)
print('d:',d)
```

## Output
<img width="1424" height="943" alt="Screenshot 2026-06-01 103528" src="https://github.com/user-attachments/assets/d8724736-fcb4-4524-9940-c328c0ecf29e" />

## Result
Thus the python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False` has been completed successfully.
<br>
<br>

# Ex 4: Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```python3
a=str("T")
b=str("a")
print(a)
print(b)
```

## Output
<img width="1324" height="760" alt="image" src="https://github.com/user-attachments/assets/f096d962-adeb-4c75-b7f9-359d43e84bf2" />

## Result
Thus the python program to print the characters `'T'` and `'a'` using character literals has been completed successfully.


<br>
<br>

# Ex 5: Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```python3

a = complex(input())
b = complex(input())

sum1 = a + b

print("A is", a)
print("B is", b)
print("Sum is", sum1)

```

## Output
<img width="1327" height="864" alt="image" src="https://github.com/user-attachments/assets/089df324-05da-479e-a863-4c2ee4c97d62" />

## Result
Thus the python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts has been completed successfully.
