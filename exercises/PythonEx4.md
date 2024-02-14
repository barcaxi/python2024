# Python Exercise 4

# Lab #1


1. Open your Pycharm project `Python2023` from your main `python` folder.
1. Create a new weekly project folder called `Ex4` -  (<kbd>File</kbd> ... <kbd>New...</kbd> ... <kbd>Directory</kbd>):

## Part 1 - Function Exercises

1.  In your `Ex4` folder create a Python program called `func1.py` to find the square of any number using the a function `sqr()`:

    ```python
    def sqr(...):
        ...


    number = 3
    print(f"sqr({number}) = {...}")
    number = 5
    print(f"sqr({number}) = {...}")
    ```

    Expected Output:
    ```
    sqr(3) = 9
    sqr(5) = 25
    ```

2.  Write a Python program called `func2.py` to find the square of a number input by the user:

    Expected Output:
    ```
    input number to square:3
    sqr(3) = 9
    ```

   
3.  Write a Python program called `func3.py` that defines four functions to perform simple arithmetic on any 2 numbers.  It should allow you to add, subtract, multiply and divide any two numbers:

    ```python
    def add(...):
        return ...


    def sub(...):
        ...


    def mul(...):
        ...


    def div(...):
        ...


    operand1 = 4
    operand2 = 2
    print(f"{operand1} + {operand2} = ...")
    print(f"{operand1} - {operand2} = ...")
    print(f"{operand1} * {operand2} = ...")
    print(f"{operand1} / {operand2} = ...")
    ```

    Expected Output:
    ```
    4 + 2 = 6
    4 - 2 = 2
    4 * 2 = 8
    4 / 2 = 2
    ```

4.  Write a Python program called `func4.py` that defines a function to determine if a given number is odd:

    ```python
    def isOdd(value):             # should return a boolean value
        ...
        ...
    

    number = 3
    if isOdd(number):
        ...
    else:
        ...

    ```

    Expected Output (`number = 3`):
    ```
    3 is odd
    ```

    Expected Output (`number = 4`):
    ```
    4 is even
    ```

5. Write a Python program called `func5.py` that defines a function `string_length()` to return the length of a given string argument.
   
    ```python
    def ...
       ...


    str = "hello"
    print(f"{str} has {string_length(str)} characters")
    ```

    Expected Output:
    ```
    hello has 5 characters
    ```

6. Write a Python program called `func6.py` that defines a function `count_char()` to return the number of times a character appears in a given string.
   
    ```python
    def count_char(character, string):
        ...


    value = "hello"
    character = 'l'
    ...
    ...    
    ```

    Expected Output:
    ```
    hello has 2 'l' character(s)
    ```

1. Write a Python program called `func7.py` that defines a function `mul_table()` that when passed a number will print a multiplication table for that number.

    Expected Output :
    ```    
    input a number:10

    Multiplication Table for 10
    10	*	1	=	10
    10	*	2	=	20
    10	*	3	=	30
    10	*	4	=	40
    10	*	5	=	50
    10	*	6	=	60
    10	*	7	=	70
    10	*	8	=	80
    10	*	9	=	90
    10	*	10	=	100
    10	*	11	=	110
    10	*	12	=	120
    ```
