salary = float(input("Enter your salary: "))
years = int(input("Enter your years of service: "))

if years > 5:
    bonus = salary * 0.05
    print("Your bonus is:", bonus)
else:
    print("No bonus (service less than or equal to 5 years)")
