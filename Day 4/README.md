# Multiplication table generator
Description :
  This project is a simple programme that generates the multiplication for a number entered by the user.It demonstrates the use of loops, user input, variables and basic calculations.
  
  Language:
    Python
    
  How to run: open an online python compiler. copy and paste the code. click the run button.Enter a number when prompted.
  
  Code :
``` python
number = int(input("Enter a number: "))

print("Multiplication Table for", number)

for i in range(1, 6):

    result = number * i
    
    print(number, "x", i, "=", result)
```

Output :
<img width="1366" height="768" alt="Day 4 output" src="https://github.com/user-attachments/assets/df04e0ab-eb1a-42ed-aad0-8c0e0b5afb2f" />
