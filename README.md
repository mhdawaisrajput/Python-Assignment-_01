# 🐍 Python Assignment – 01
**Topics:** Variables, Data Types & Operators

This assignment covers variables, data types, arithmetic, assignment, comparison, logical operators, and real-life examples.

```python
# ------------------------------------
# 📝 Q1: Variables & Data Types
# ------------------------------------

name: str = "Muhammad Awais"
age: int = 24
is_student: bool = True

student_status: str = "Yes" if is_student else "No"

print(f"Hi, I am {name}, I am {age} years old and I am a student in PIAIC: {student_status}")

print("\n--- Data Types ---")
print("Name Data Type        :", type(name))
print("Age Data Type         :", type(age))
print("is_student Data Type  :", type(is_student))

# ------------------------------------
# ➕ Q2: Arithmetic Operators
# ------------------------------------

x: int = 20
y: int = 6

print(f"Addition        :  x({x}) + y({y}) = {x + y}")
print(f"Substraction    :  x({x}) - y({y}) = {x - y}")
print(f"Multiplication  :  x({x}) * y({y}) = {x * y}")
print(f"Division        :  x({x}) / y({y}) = {x / y}")
print(f"Floor Division  :  x({x}) // y({y}) = {x // y}")
print(f"Modulus         :  x({x}) % y({y}) = {x % y}")
print(f"Exponent        :  x({x}) ** y({y}) = {x ** y}")

# ------------------------------------
# 🔧 Q3: Assignment Operators
# ------------------------------------

num: int = 10
num += 5
print(f"Value after addition of 10 + 5 is              :  {num}")

num *= 2
print(f"Value after multiplication of 15 * 2 is        :  {num}")

num -= 4
print(f"Final value of all operators after 30 - 4 is   :  {num}")

# ------------------------------------
# ⚖️ Q4: Comparison Operators
# ------------------------------------

a: int = 15
b: int = 12

print(f"a({a}) > b({b})  : {a > b}")
print(f"a({a}) < b({b})  : {a < b}")
print(f"a({a}) == b({b}) : {a == b}")
print(f"a({a}) != b({b}) : {a != b}")
print(f"a({a}) >= b({b}) : {a >= b}")
print(f"a({a}) <= b({b}) : {a <= b}")

# ------------------------------------
# 🧠 Q5: Logical Operators
# ------------------------------------

p: bool = True
q: bool = False

print(f"p({p}) AND q({q})  :  {p and q}")
print(f"p({p}) OR q({q})   :  {p or q}")
print(f"NOT p({p})         :  {not p}")
print(f"NOT q({q})         :  {not q}")

# ------------------------------------
# 💰 Q6: Real-Life Example
# ------------------------------------

price_per_notebook: int = 80
quantity: int = 7
money_available: int = 600

total_price: int = price_per_notebook * quantity
is_enough: bool = money_available >= total_price

print(f"Price of one notebook: {price_per_notebook} rupees")
print(f"Total notebooks: {quantity}")
print(f"Total price: {total_price} rupees")
print(f"Money available: {money_available} rupees")
print(f"Can you buy them? {'Yes' if is_enough else 'No'}")
print(f"Remaining amount is : {money_available % total_price}")

# ------------------------------------
# ➗ Q7: Sum & Compare Two Numbers
# ------------------------------------

first_number = int(input("Enter your first number: "))
second_number = int(input("Enter your second number: "))

total: int = first_number + second_number
print(f"The sum of {first_number} and {second_number} is: {total}")

if first_number > second_number:
    print(f"{first_number} is greater than {second_number}")
elif first_number < second_number:
    print(f"{first_number} is less than {second_number}")
else:
    print(f"{first_number} is equal to {second_number}")

# ------------------------------------
# 🙋 About Me
# ------------------------------------

print("Hello! I am Muhammad Awais, a Python enthusiast and PIAIC student learning programming fundamentals. 💻🌐")
