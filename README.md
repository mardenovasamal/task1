Utils
This Java class provides utility methods for solving common problems in mathematics and computer science.

Methods
The following methods are available in the Utils class:

findMin(int n, int[] arr): Finds the minimum value in an array of integers.
findAverage(int n, int[] arr): Calculates the average of the elements in an array of integers.
isPrime(int n): Checks whether an integer is a prime number.
factorial(int n): Calculates the factorial of an integer.
fibonacci(int n): Calculates the nth element in the Fibonacci sequence using recursion.
power(int a, int n): Calculates a raised to the power of n.
reverseArray(int n, int[] arr): Reverses the order of the elements in an array of integers using recursion.
isAllDigits(String s): Checks whether a string consists only of digits.
binomialCoefficient(int n, int k): Calculates the binomial coefficient C(n,k) using recursion.
gcd(int a, int b): Calculates the greatest common divisor of two integers using recursion.
Usage
To use the Utils class in your Java project, simply include the Utils.java file in your source code directory and import the class where needed:
import com.example.Utils;

public class Main {
    public static void main(String[] args) {
        int[] arr = {10, 1, 32, 3, 45};
        int minVal = Utils.findMin(5, arr);
        System.out.println("Minimum value is: " + minVal);
    }
}
