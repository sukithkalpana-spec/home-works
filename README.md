# home-works


# Calculate the area of a triangle
base =  float(input("Enter the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))
area = 0.5 * base * height

print("the area of the triangle is:",area)


# print the eligibility to vote

age =int(input("Enter your age: "))

if age >=18:
    print("You are eligible to vote. ")
else:
    print("You are not eligible for vote. ")


# Check whether a number Positive,Negative or Zero

num = float(input("Enter a number: "))

if num > 0:
    print("The number is Positive.")
elif num < 0:
    print("The number is Negative.")
else:
    print("The number is Zero.")


# Check whether a year is a leap year or not

year = int(input("Enter a year: "))

if year % 400 == 0:
    print(year, "is a Leap year.")
elif year % 100 == 0:
    print(year, "is not a Leap year")
elif year % 4 == 0:
    print(year, "is a Leap year.")
else:
    print(year,"is not a Leap year.")


# Check if a triangle is equilateral, isosceles, scalene

a = float(input("Enter side a: "))
b = float(input("Enter side b: "))
c = float(input("Enter side c: "))

if a == b == c:
    print("The triangle is Equilateral.")
elif a == b or b ==c or a ==c:
    print("The triangle is Isosceles.")
else:
    print("The triangle is Scalene.")



# Find the minimum of 3 numbers

a = float(input("Enter number a: "))
b = float(input("Enter number b: "))
c = float(input("Enter number c: "))

if a <= b and a <= c:
    print("The minimum number is a:")
elif b <= a and b <= c:
    print("The minimum number is b:")
else:
    print("The minimum number is c:")



# Print even numbers from 1-10
for i in range(1,11):
     if i % 2 == 0:
         print(i)




#  Print the sum of 1-10 numbers
total = 0
for i in range(1,11):
     total = total + i
     print("The sum of 1-10 numbers is :",total)


# Print the sum of even numbers from 1-10
total = 0
for i in range(1,11):
     if i % 2 == 0:
         total = total + i
         print("The sum of even numbers from 1-10 is :",total)



# Print square numbers which are less than 100
for i in range (1,11):
    square = i * i
    if square < 100:
        print(square)



