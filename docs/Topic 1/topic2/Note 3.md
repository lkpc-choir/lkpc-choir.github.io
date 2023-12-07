# Note 3

"""
This function takes in a list of numbers and returns the sum of all the numbers.

Parameters:
- numbers (list): A list of numbers.

Returns:
- sum (int): The sum of all the numbers in the list.
"""

def calculate_sum(numbers):
    sum = 0
    for num in numbers:
        sum += num
    return sum
