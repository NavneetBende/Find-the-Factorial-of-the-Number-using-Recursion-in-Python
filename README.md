# Find-the-Factorial-of-the-Number-using-Recursion-in-Python

Factorial of a Number using Recursion in Python
Here, on this page, we will learn how to find the Factorial of a Number using Recursion in Python programming language. We will discuss various methods to solve the given problem.

Factorial of a Number using Recursion

Method Discussed :
Method 1 : Using Recursion
Method 2 : Using Iteration.
Algorithm ( Method 1 )
Call function getFactorial(num)
Set base case when num== 0 return 1
Other cases return num * getFactorial(num-1);
Time and Space Complexity :
Time complexity: O(N)
Space complexity: O(1)
Auxiliary Space complexity (Function call stack): O(N)
Factorial of a Number using Recursion in Python
Python Code
Run
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)


num = 5
print("Factorial of", num, "is", factorial(num))
Output
Factorial of 5 is 120
Algorithm ( Method 2 )
Initialize fact = 1
If num < 0 : Print Error as we can’t calculate factorial of a negative number
Else run an iterative loop in the iteration of (i) between [1, num]
Set fact = fact * i
Print the value of the fact.
Time and Space Complexity :
Time complexity: O(N)
Space complexity: O(1)
Run
def factorial(n):
    res = 1
    for i in range(2, n + 1):
        res *= i
    return res


num = 5
print("Factorial of", num, "is", factorial(num))
Output
Factorial of 5 is 120
