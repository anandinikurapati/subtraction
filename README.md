# subtraction
num1 = 10
num2 = 5
result = num1 - num2
print("Subtraction using the Minus Operator:", result)
# approach-2
def subtract_numbers(num1, num2):
    result = num1 - num2
    return result
    
number1 = 40
number2 = 18
subtraction_result = subtract_numbers(number1, number2)
 
print(f"Subtraction using Function: {subtraction_result}")
# approach-3
subtract = lambda x, y: x - y
num1 = 30
num2 = 15
result = subtract(num1, num2)
print("Subtraction using Lambda Function:", result)
