# Pytthon Poject

I am an aspiring Python programmer with a solid interest in problem-solving, data analysis and the development of practical software solutions. Throughout my Data Technician training, I completed a series of Python projects and exercises that demonstrate my technical growth, analytical thinking, and commitment to continuous learning.

---

## 🛠️ Technical Skills

- **Python Programming**
  - Loops, conditionals, functions, input validation and menu-driven logic
  - Error handling and flow control
- **Data Analysis**
  - Pandas for data manipulation and exploration
- **Data Visualisation**
  - Exposure to visualisation workflows and tools (inspired by Kaggle courses & YouTube tutorials)
- **Tools & Platforms**
  - Google Colab
  - Kaggle Notebooks
  - Git & GitHub
  - Jupyter Notebooks

---

## 🚀 Projects & Practical Work

**ATM Simulation (Python)**
- PIN validation system
- Menu-based operations (balance inquiry, withdraw, deposit, exit)
- Demonstrates conditional logic, user input handling and state management
```Python
pin1=1234 
pin2=0 
bal=float(3692.36) 
pin2 = int(input("Enter your four digit pin: ")) 
while pin2 != pin1: 
  print("Pin Invalid! Try again") 
  pin2 = int(input("Enter your four digit pin: ")) 
print("1-Account Balance \n2-Depositing Money \n3-Withdraw Money \n4-Exit") 
m_menu = int(input("Enter the number corresponding to the desired option:\n")) 
while m_menu == 0 or m_menu >= 6: 
  print("Invalid opption.") 
  m_menu = int(input("Enter the number corresponding to the desired option:\n")) 
if m_menu == 1: 
  print(f"Your current Balance is £{bal}") 
  print("Thank you for unising our services") 
elif m_menu == 2: 
  bal1 = float(input("Enter the amount you would like to deposit. \n£:")) 
  bal += bal1 
  print(f"Your current Balance is £{bal}") 
  print("Thank you for unising our services") 
elif m_menu == 3: 
  bal1 = float(input("Enter the amount you would like to withdraw. \n£:")) 
  bal -= bal1 
  print(f"Your current Balance is £{bal}") 
  print("Thank you for unising our services") 
else: 
  print("Thank you for unising our services")
````

**FizzBuzz Challenge**
- Iteration and conditional structures to solve a classic software interview task
```python
for n in range(1, 101):
    if n % 3 == 0 and n % 5 == 0:
        print("FizzBuzz")
    elif n % 3 == 0:
        print("Fizz")
    elif n % 5 == 0:
        print("Buzz")
    else:
        print(n)
````

**Python Practice Exercises**
Examples include:
- Palindrome checker
```Python
word = input("Enter a word: ") 
if word == word[::-1]: 
    print(f"{word} is a palindrome.") 
else: 
    print(f"{word} is not a palindrome.") 
````
- Prime number checker
```Python
n = int(input("Enter a number: ")) 
if n < 2: 
    print(f"{n} is not a prime number.") 
else: 
   n >= 2 
   for i in range(2, n): 
       if n % i == 0: 
           print(f"{n} is not a prime number.") 
           break 
   else: 
    print(f"{n} is a prime number")
````
- Leap year validation
```Python
year = int(input("Enter a year: "))
def is_leap(year):
  if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    return True
  else:
    return False
print(is_leap(year))
````   
- Even/odd number logic
```Python
number = int(input("Enter a number: ")) 
if number % 2 == 0: 
    print(f"{number} is an even number.") 
else: 
    print(f"{number} is an odd number.")
````
- Numerical digit summation
- Basic arithmetic and user interaction scripts
```Python
num1 = int(input("Enter the first number: ")) 
num2 = int(input("Enter the second number: ")) 
sum1 = num1 + num2 
print(f"The sum of {num1} and {num2} is {sum1}.")
````

**Data Analysis & Visualisation**
- Exposure to Pandas and exploratory analysis via Kaggle and YouTube materials

---

## 🌱 Learning & Interests

I am continuously exploring:
- Data science and analytics workflows
- Business intelligence reporting
- Python for automation
- Data visualisation techniques

---

## 📫 Connect with Me

- **LinkedIn:** https://www.linkedin.com/in/edmillson-as

I’m open to collaborating on projects, contributing to Python/data initiatives, and learning from other developers and data professionals. Feel free to explore my repositories and get in touch!

---
