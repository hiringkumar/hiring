# Input: Ask the user to enter a number
number = int(input("Enter a number: "))

# Find the last digit using modulus operator
last_digit = abs(number) % 10  # Use abs() to handle negative numbers

# Display the last digit
print(f"The last digit of the number is: {last_digit}")

# Check if the last digit is divisible by 5
if last_digit % 5 == 0:
    print("The last digit is divisible by 5.")
else:
    print("The last digit is not divisible by 5.")
