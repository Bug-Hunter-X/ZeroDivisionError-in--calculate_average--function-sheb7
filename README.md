# Python Bug: ZeroDivisionError in `calculate_average`
This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating the average of an empty list.
The `bug.py` file contains the buggy code, while `bugSolution.py` demonstrates the corrected version.
The error arises because the function attempts division by zero if the input list is empty. The solution involves explicitly checking if the list is empty before performing the division.