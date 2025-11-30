# -Calculations-and-Return-Values
# Calculations and Return Values
# Jonathan Haynes
# Date: 11/26/2025
# Description: Program that collects user data, converts it, and prints results with timestamps.


from datetime import datetime

# ----------------------------------------------
# Function: convertData(value)
# Converts Fahrenheit to Celsius using:
#   (F - 32) * 5/9
# ----------------------------------------------
def convertData(value):
    return (value - 32) * (5/9)


# ----------------------------------------------
# Function: getInput()
# Collects user entries, converts them,
# prints timestamped saved information.
# ----------------------------------------------
def getInput():
    print(f"You selected 1 at {datetime.now()}")
    num = int(input("How many entries are you inputting?\n"))

    for i in range(num):
        date = input("\nEnter a date:\n")
        value = float(input("Enter the highest temp for the inputted date:\n"))

        # Calling convertData() with numerical value; returns converted temperature
        converted = convertData(value)

        print(f"\nThe following was saved at {datetime.now()} :")
        print(f"{date},{value},{converted}\n")


# ----------------------------------------------
# Main Menu
# ----------------------------------------------
print("Student1234's Spreadsheet Automation Menu")
print("Choose a number from the following options")
print("1 Input Data")
print("2 View Current Data")
print("3 Generate Report")

choice = input()

if choice == "1":
    getInput()
else:
    print("Error: The chosen functionality is not implemented yet")

    # Calculations and Return Values
# Jonathan Haynes
# Date: 11/26/2025
# Description: Program that collects user data, converts it, and prints results with timestamps.

from datetime import datetime

# ----------------------------------------------
# Function: convertData(value)
# Converts pounds (lbs) to kilograms (kg)
# Formula: lbs / 2.205
# ----------------------------------------------
def convertData(value):
    return value / 2.205


# ----------------------------------------------
# Function: getInput()
# Collects user entries, converts them,
# prints timestamped saved information.
# ----------------------------------------------
def getInput():
    print(f"You selected 1 at {datetime.now()}")
    num = int(input("How many entries are you inputting?\n"))

    for i in range(num):
        date = input("\nEnter a date:\n")
        value = float(input("Enter the weight (lbs) for the inputted date:\n"))

        # Calling convertData() with numerical value; returns converted kg
        converted = convertData(value)

        print(f"\nThe following was saved at {datetime.now()} :")
        print(f"{date},{value},{converted}\n")


# ----------------------------------------------
# Main Menu
# ----------------------------------------------
print("Student1234's Spreadsheet Automation Menu")
print("Choose a number from the following options")
print("1 Input Data")
print("2 View Current Data")
print("3 Generate Report")

choice = input()

if choice == "1":
    getInput()
else:
    print("Error: The chosen functionality is not implemented yet.")


# Calculations and Return Values
# Jonathan Haynes
# Date: 11/26/2025
# Description: Program that collects user data, converts it, and prints results with timestamps.

from datetime import datetime

# ----------------------------------------------
# Function: convertData(value)
# Converts inches to centimeters
# Formula: in * 2.54
# ----------------------------------------------
def convertData(value):
    return value * 2.54


# ----------------------------------------------
# Function: getInput()
# Collects user entries, converts them,
# prints timestamped saved information.
# ----------------------------------------------
def getInput():
    print(f"You selected 1 at {datetime.now()}")
    num = int(input("How many entries are you inputting?\n"))

    for i in range(num):
        date = input("\nEnter a date:\n")
        value = float(input("Enter the rainfall amount (inches):\n"))

        # Calling convertData() with numerical value; returns converted cm
        converted = convertData(value)

        print(f"\nThe following was saved at {datetime.now()} :")
        print(f"{date},{value},{converted}\n")


# ----------------------------------------------
# Main Menu
# ----------------------------------------------
print("jonhay2001" Spreadsheet Automation Menu")
print("Choose a number from the following options")
print("1 Input Data")
print("2 View Current Data")
print("3 Generate Report")

choice = input()

if choice == "1":
    getInput()
else:
    print("Error: The chosen functionality is not implemented yet")

    
