
    # 1. Discount Calculator
    '''
bill = float(input("Enter amount: "))
if bill > 1000:
    discount = bill * 0.2
elif bill > 500:
    discount = bill * 0.1
else:
    discount = 0
final_amount = bill - discount
print(final_amount)
''',
    # 2. Grade Categorizer
    '''
marks = int(input("Enter marks: "))
if marks >= 90 and marks <= 100:
    print("Grade A")
elif marks >= 70:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
''',
    # 3. Age Group Classifier
    '''
age = int(input("Enter age: "))
if age < 13:
    print("Child")
elif age <= 19:
    print("Teen")
elif age <= 59:
    print("Adult")
else:
    print("Senior")
''',
    # 4. Even/Odd and Multiple of 5
    '''
num = int(input("Enter number: "))
if num % 2 == 0 and num % 5 == 0:
    print("Even and divisible by 5")
elif num % 2 != 0 and num % 5 == 0:
    print("Odd and divisible by 5")
elif num % 2 == 0:
    print("Even and not divisible by 5")
else:
    print("Odd and not divisible by 5")
''',
    # 5. Login System
    '''
username = input("Enter username: ")
if username in ['john', 'amy', 'sita']:
    print("Login successful")
else:
    print("Access denied")
''',
    # 6. Number Comparison Game
    '''
a = int(input("Enter number: "))
b = int(input("Enter number: "))
if a > b:
    print("First is greater")
elif b > a:
    print("Second is greater")
else:
    print("Equal")
''',
    # 7. Voting and Driving Eligibility
    '''
age = int(input("Enter age: "))
if age >= 21:
    print("Can vote and drive")
elif age >= 18:
    print("Can vote")
else:
    print("Not eligible")
''',
    # 8. Leap Year Check
    '''
year = int(input("Enter year: "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print("Leap year")
else:
    print("Not a leap year")
''',
    # 9. Login with Role
    '''
username = input("Enter username: ")
role = input("Enter role: ")
if username in ['john', 'amy', 'sita'] and role in ['admin', 'manager']:
    print("Login successful")
else:
    print("Login failed")
''',
    # 10. Arithmetic Operations
    '''
a = int(input("Enter number: "))
b = int(input("Enter number: "))
op = input("Enter operator: ")
if op == '+':
    print(a + b)
elif op == '-':
    print(a - b)
elif op == '*':
    print(a * b)
elif op == '/':
    print(a / b)
else:
    print("Invalid")
''',
    # 11. Weather Alert System
    '''
temp = float(input("Enter temp: "))
if temp > 40:
    print("Heat Alert")
elif temp > 30:
    print("Warm")
else:
    print("Normal")
''',
    # 12. Password Strength
    '''
pwd = input("Enter password: ")
if len(pwd) >= 8 and '@' in pwd:
    print("Strong")
else:
    print("Weak")
''',
    # 13. ATM Withdrawal
    '''
bal = 10000
amt = int(input("Enter amount: "))
if amt <= bal and amt % 100 == 0:
    print("Success")
else:
    print("Invalid")
''',
    # 14. Divisibility Check
    '''
num = int(input("Enter number: "))
if num % 3 == 0 and num % 5 == 0:
    print("Div by 3 and 5")
elif num % 3 == 0:
    print("Div by 3")
elif num % 5 == 0:
    print("Div by 5")
else:
    print("Not divisible")
''',
    # 15. Product Availability
    '''
item = input("Enter product: ")
if item in ['pen', 'pencil', 'eraser']:
    print("Available")
else:
    print("Not found")
''',
    # 16. Triangle Validity
    '''
a = int(input("Enter side: "))
b = int(input("Enter side: "))
c = int(input("Enter side: "))
if a + b > c and a + c > b and b + c > a:
    print("Valid")
else:
    print("Invalid")
''',
    # 17. Max of Three Numbers
    '''
a = int(input("Enter number: "))
b = int(input("Enter number: "))
c = int(input("Enter number: "))
if a >= b and a >= c:
    print(a)
elif b >= a and b >= c:
    print(b)
else:
    print(c)
''',
    # 18. Marks Validity
    '''
mark = int(input("Enter mark: "))
if mark >= 0 and mark <= 100:
    print("Valid")
else:
    print("Invalid")
''',
    # 19. Login Attempt System
    '''
user = input("Enter username: ")
pwd = input("Enter password: ")
if user == "admin" and pwd == "1234":
    print("Login successful")
else:
    print("Login failed")
''',
    # 20. Electricity Bill
    '''
unit = int(input("Enter units: "))
if unit <= 100:
    bill = unit * 5
elif unit <= 200:
    bill = unit * 7
else:
    bill = unit * 10
print(bill)
'''

