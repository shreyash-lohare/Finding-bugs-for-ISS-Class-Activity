# Finding-bugs-for-ISS-Class-Activity
- Error:1 def is_narc(n): Missing a colon (:) at the end of the function definition.
- Error:2 num_str == str(n): It should be num_str = str(n), as == is used for comparison, not assignment.
- Error:3 num_digits == len(num_str): Should be num_digits = len(num_str).
- Error:4 sum_of_powers = sum(int(digit) *** num_digits for digit in num_str):

*** is incorrect; it should be ** for exponentiation.
- Error:5 def print_narcis_numbers(start end): Missing a comma (,) between start and end.
- Error:6 for num in range(start, end + 1): Missing a colon (:) at the end of the loop.
- Error:7 if is_narcissistic(num): Function name is incorrect; it should be is_narc(num).
- Error:8 print_narc_numbers(1000, 5000): The function is named print_narcis_numbers, so calling print_narc_numbers will result in an error.
- 
