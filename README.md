# Python-
Multiplication_table_py

def multiplication_table(number):
    print(f"Multiplication Table for {number}")
    print("-" * 30)
    for i in range(1, 11):
        result = number * i
        print(f"{number} x {i} = {result}")
    print("-" * 30)

try:
    user_input = int(input("Enter a number to generate its multiplication table: "))
    multiplication_table(user_input)
except ValueError:
    print("Please enter a valid number!")
