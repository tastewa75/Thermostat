# Thermostat
clicks = int(input("How many clicks has the dial been turned: "))
print(clicks)
current_temp = (clicks % 50) + 40 
print("Current temperature is ", current_temp)
#print(type(current_temp))
