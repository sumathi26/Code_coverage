# 1. Program Development:
          create a file named calculator.py 

# 2. Partial Unit Tests:
          We'll write unit tests for add, divide, and is_even.
          a) Why these functions?
                add: Basic arithmetic, easy to test.
                divide: Needs coverage for valid division and error handling (division by zero).
                is_even: Logical function that should cover even and odd scenarios.
          create a file named test_calculator.py 
          write the unit tests.

# 3. Measure Code Coverage:
          a) Tool Used: coverage.py with pytest
          b) How to Install & Run:
                Install: pip install pytest coverage
                Run tests with coverage: coverage run -m pytest
                                         coverage report -m
          c) Initial Coverage Percentage: 75%-85%
# 4. Improve Coverage:
          a) What was improved:
                Added tests for:
                    subtract function
                    multiply function
          b) Re-run coverage.py: coverage run -m pytest
                                 coverage report -m
# Summary of Each Step
# 1. Program Development
A modular calculator with functions for basic arithmetic, including error handling for division.
# 2. Partial Unit Tests
Tested add() and divide() first to establish coverage baseline and handle an edge case.
# 3.Code Coverage Measurement
Used coverage.py with pytest. Initial coverage: ~83% for calculator.py.
# 4. Improved Coverage
Added tests for subtract() and multiply(). Final coverage: 96%.






