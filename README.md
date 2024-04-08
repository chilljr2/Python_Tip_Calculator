# Python_Tip_Calculator

https://replit.com/@clintonhill11/CJ-tip-calculator-start

print("Welcome to Clinton's tip calulcator!")

bill = float(input("What was the total bill? $"))

tip = int(input("How much tip would you like to give? 10, 12, or 15? "))

people = int(input("How many people to split the bill? "))

bill_with_tip = tip / 100 * bill + bill

print(f"Each person should pay: {bill_with_tip / people}")
