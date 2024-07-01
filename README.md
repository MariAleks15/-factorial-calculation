# -factorial-calculation
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Get the number from the user
number = int(input("Enter a number: "))

# Check that the number is non-negative
if number < 0:
    print("Factorial is only defined for non-negative numbers.")
else:
    print(f"The factorial of {number} is {factorial(number)}")
