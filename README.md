# Please indicate your weight in kilograms
weight = float(input("Enter your weight in kilograms: "))
# Please indicate your height in meters
height = float(input("Enter your height in meters: "))
# Calculate the BMI
bmi = weight / (height ** 2)
print (f"Your bmi is: {bmi:.2f}")
