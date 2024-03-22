In this assignment, you should write your code in a **readable** way.

Your function definitions should have **appropriate docstrings**.

# Assignment 5a: Hours, Minutes, and Seconds (revisited)

**Note:** This is the same task as Assignment 1, but the code is required in a different form.

Define a **function** `to_hms(seconds)` that:

1. Takes in an integer argument `seconds` containing the number of seconds
2. Validates the variable `seconds` (positive integers only)
3. If the input is valid, return a **list** containing the number of hours, minutes, and seconds
4. If the input is invalid, **display** an error message.


### Example output

    >>> to_hms()
    [0, 0, 10]
    >>> to_hms(61)
    [0, 1, 1]
    >>> to_hms(7199)
    [1, 59, 59]
    >>> to_hms("10")
    Unsupported input type.

# Submission

Before submitting your code, run the automated tests on your functions. In the shell, type `python test_main.py` and press enter to see the results of the testing.
