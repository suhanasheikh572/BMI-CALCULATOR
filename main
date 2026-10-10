# BMI Calculator

print("======BMI CALCULATOR======")

while True :
    try:
        wgt = float(input("Enter your weight in kg:"))   
        if wgt > 0 :
            break
    except ValueError:
        print("Error : Please enter numeric value (e.g.,45.5 etc.)")

while True :
    try:
        hgt = float(input("Enter your height in m:"))
        if hgt > 0:
            break
    except ValueError:
        print("Error : Please enter a numeric value for height (e.g., 1.75)")
        
bmi = wgt / (hgt ** 2)

print("Your BMI is:", round(bmi, 2))

if(bmi < 18.5):

    print("You are underweight")

elif(bmi >= 18.5 and bmi < 24.9):

    print("You are normal weight")

elif(bmi >= 25 and bmi <29.9 ):

    print("You are overweight")

elif(bmi >= 30):

    print("You are obese")

