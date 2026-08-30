import math

#  Let's get the x and y coordinates for both points from the user
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

x_diff = x2 - x1
y_diff = y2 - y1

sum_of_squares = math.pow(x_diff, 2) + math.pow(y_diff, 2)
distance = math.sqrt(sum_of_squares)

print(f"\nThe distance between the two points is: {distance:.2f}")

