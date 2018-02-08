# Make-Change
Replacing pennies with appropriate coins


pennies = input("How many pennies do you have?\n:")
pennies = int(pennies)
quarters = pennies//25
pennies = pennies % 25
dimes = pennies//10
pennies = pennies % 10
nickels = pennies//5
pennies = pennies % 5
print("Quarters: " + str(quarters))
print("Dimes: " + str(dimes))
print("Nickels: " + str(nickels))
print("Pennies: " + str(pennies))
