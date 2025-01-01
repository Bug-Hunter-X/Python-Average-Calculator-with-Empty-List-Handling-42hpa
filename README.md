# Python Average Calculator

This repository contains a simple Python function to calculate the average of a list of numbers.  The function is designed to gracefully handle the case of an empty input list, preventing a `ZeroDivisionError`.

## Function: `calculate_average(numbers)`

This function takes a list of numbers as input and returns their average. If the input list is empty, it returns 0.

## How to Use

1.  Clone this repository.
2.  Import the `calculate_average` function into your project.
3.  Pass a list of numbers to the function to calculate the average.

## Example

```python
from average_calculator import calculate_average

numbers = [10, 20, 30, 40, 50]
average = calculate_average(numbers)
print(f"The average is: {average}")  # Output: The average is: 30.0

empty_list = []
average_empty = calculate_average(empty_list)
print(f"The average of an empty list is: {average_empty}")  # Output: The average of an empty list is: 0
```