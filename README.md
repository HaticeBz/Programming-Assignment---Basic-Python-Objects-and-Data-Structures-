#Multiplication of three numbers 
firstNumber = int(input("First number :"))
secondNumber = int(input("Second number :"))
thirdNumber = int(input("Third number :"))

print("Multiplication of numbers : {}".format(firstNumber * secondNumber * thirdNumber))


#Body Mass Index
height = int(input("Enter your height :"))
kg = int(input("Enter your kg :"))

bodyMassIndex = kg/(height*height)

print("Your body mass index is :",(bodyMassIndex))


#Kilometer and fuel
km = int(input("How many kilometers did you? :"))
fuel = float(input("How much fuel does the car consume per kilometer? :"))

print("Amount to be paid : {} TL".format(km * fuel))


#Name, Surname, Phone number
name = input("Enter your name :")
surname = input("Enter your surname :")
phoneNumber = int(input("Enter your phone number(Enter without 0) :"))

together = [surname,phoneNumber,name]

print("Name : {}\nSurname : {}\nPhone number : {}".format(together[2],together[0],together[1]))


#Swapping numbers
firstNumber = int(input("Enter first number :"))
secondNumber = int(input("Enter second number :"))

print("First number is : {}\nSecond number is : {}".format(secondNumber,firstNumber))


#Finding the hypotenuse of a right triangle
firstSide = int(input("Enter first side length :"))
secondSide = int(input("Enter second side length :"))

hypotenuse = (firstSide ** 2 + secondSide ** 2) ** 0.5

print("Hypotenuse of right triangle is :", hypotenuse)
