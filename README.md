Follow TDD approach to solve the below problem

Class `FizzBuzz` should have a method which will take a number as input and return a String based on the below condition

- Should return `fizz` if the number is divisible by 3.
- Should return `buzz` if the number is divisible by 5.
- Should return `fizzbuzz` if the number is divisible by 15.
- Should return the same number if no requirement is fulfilled.
- Should throw `IllegalArgumentException` if the number is less than or equal to 0.

Make sure to write test case first for the above scenario before writing the actual code

Mockito Example
-

Create a class `AnagramFizzBuzz` with TDD Approach which will have a method with below signature

`public String getAnagram(String input)`

The above method should have the below functionality:

- It should call the fizz buzz with input and return the string after reversing it.

Note: Use Mockito to mock the `FizzBuzz` class.
