# 🐍 Python Fundamentals Project – Data Technician Bootcamp

---
## 📖 Overview
This project was completed during the **Data Technician Bootcamp** and focuses on building a strong foundation in Python programming. The exercises explored **variables, user interaction, control flow, and loops** to develop logical problem-solving skills. The goal was to use Python to perform calculations, build decision-making logic, and interact with users through input/output.

---
## 🛠 Skills Demonstrated
- **Variables & Data Types**  
  - Declared and manipulated variables of different types (`int`, `float`, `str`).  
  - Practiced type casting to convert between strings, integers, and floats.

- **Printing & User Input**  
  - Used the `print()` function to display results and messages.  
  - Applied the `input()` function to collect user responses and make programs interactive.

- **Conditional Logic**  
  - Implemented `if`, `elif`, and `else` statements to control program flow.  
  - Built decision-making structures such as customer classification (Gold, Silver, Bronze) based on sales thresholds.

- **Loops**  
  - Created `for` loops to iterate over ranges and collections.  
  - Applied `while` loops for repeated tasks until conditions were met.  
  - Used `break` and `continue` to refine loop behavior.

---
## 🔢 Applications
- **Calculations**: Performed arithmetic operations (addition, subtraction, multiplication, division, modulus, floor division, exponentiation).  
- **Logic Building**: Designed programs to classify customers, compare numbers, and check pass/fail conditions.  
- **User Interaction**: Built small scripts that ask for user input, process it, and return meaningful results.  

---
## 🎯 Key Insights
- Learned how to combine **variables, operators, and conditions** to build logical programs.  
- Understood how **loops** simplify repetitive tasks.  
- Gained confidence in writing **interactive scripts** that respond to user input.  
- Practiced debugging and fixing syntax errors to strengthen problem-solving skills.

---

## 💻 Example Code Snippets

### 1. Customer Classification
```python
annualSales = 300000

if annualSales >= 500000:
    print("Gold Customer")
elif annualSales >= 300000:
    print("Silver Customer")
elif annualSales >= 100000:
    print("Bronze Customer")

print("Thank you for your business")
2. Number Comparison
python
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

if num1 > num2:
    print("The larger number is:", num1)
elif num2 > num1:
    print("The larger number is:", num2)
else:
    print(num1, "is equal to", num2)
3. FizzBuzz
python
for i in range(1, 21):  # shortened to 20 for demo
    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
4. Pass/Fail Check
python
mark = int(input("Enter student mark: "))
threshold = 60

if mark >= threshold:
    print("Pass")
else:
    print("Fail")



📍 Conclusion
This project highlights the core building blocks of Python programming: variables, input/output, conditionals, and loops. These fundamentals form the backbone of more advanced topics such as data analysis, automation, and application development. By mastering these basics, the foundation is set for tackling real-world problems with Python.
