# elisasyr.github.io
This is an assignment №3 
# Assignment 3 
# This code takes a user input, gives user a choice and convert a user's input into either a base 2 number or a base 16 number. 

value = input("Please enter a number from 0 to 10:")
v1 = int(value)
conversion = bin(v1)
conversion2 = hex(v1)
choice = input ("Enter 1 for a transformation into a base 2 number.\nEnter 2 for a transformation into a base 16 number:")
choice = int(choice)
if choice == 1:
    print(f'You entered {v1} and 1 and the result is {conversion} It is a base 2 number')
if choice == 2:
    print(f'You entered {v1} and 2 and the result is {conversion2} It is a base 16 number')
