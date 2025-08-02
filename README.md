# leap-year-calculator
helps to determine whether a year entered by a user is a leap year or not
#Divisibility by 4,if the year enetered by a user divisible by 4 with no remainder , it is considered likely a leap year.
#Divisibility by 100,if the year enetered by a user divisible by 100 with no remainder , it is considered unlikely to be a leap year except it is also cleanly divisible by 400.
print("welcome to the leap year calculator")
year = int(input("enter a year you want to check"))
if year %4==0:
  if year%100==0:
    if year%400==0:
     print("it is a leap year") 
    else:
      print("it is not a leap year")
  else:
    print("it is a leap year")
else:
  print("it is not a leap year")

