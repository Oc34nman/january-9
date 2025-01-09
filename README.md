# january-9


#function definition
def add_numbers(a, b):
    return a + b


result = add_numbers(5, 3) #function call
print("The sum of the number is:", result)

def circleArea(a):
    return 3.14*a*a

result = circleArea(5)
print("the sum of the numbers is:", result)

def FtoC(F):
    celsius = (fahrenheit - 32) * 5 / 9
    print("celcius is: ", round(celsius, 3))
    return FtoC

fahrenheit = 40
FtoC(fahrenheit)

def AveOfThree(a, b, c):
    Average = (a + b + c) // 3
    return Average


Average = AveOfThree(56, 43, 3)
print("the average of three is: ", Average)
