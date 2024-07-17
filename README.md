# Nika
# Simple program to add two numbers

# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Taking input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Calculating the sum
result = add_numbers(num1, num2)

# Displaying the result
print("The sum of {} and {} is {}".format(num1, num2, result))
