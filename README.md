# Total-salary-after-5-years-including-bonus

name=str(input("Enter your name: "))
salary=int(input("Enter your salary: "))
year=int(input("Enter your year: "))

if(year>=5):
    bonus=salary*(5/100)
    print("Bonus Amount: ",bonus)
    salary=salary+bonus
    print("Total Salary after bonus: ",salary)
else:
    print("you are not capable for the Bonus")
