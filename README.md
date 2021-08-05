#body mass index
#get the variables of weight and height

weight = int(input("tell me your weight :"))
height = float(input("tell me your height :"))

#create the booleans:

if weight/height**2 < 18.5:
    print ("you have : Underweight")

if weight/height**2 >= 18.5 and weight/height**2 <25:
    print("you have : Normal")

if weight/height**2 >= 25 and weight/height**2 < 30:
    print("you have : Overweight") 

if weight/height**2 > 30:
    print("you have : Obesity")    

