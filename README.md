# Module-3

**Task1:**

a = int(input("Enter a number: ")) → Asks the user to type a number.
if (a % 2 == 0):

% is the modulus operator, it gives the remainder after division.

If the remainder is 0, that means the number is divisible by 2 → hence it’s an even number.

print(a, "is an even number")

If the condition is true, it prints:

else:

    print(a, "is an odd number")

If the condition is false (remainder ≠ 0), the number is not divisible by 2, so it must be an odd number.


**Task2:**


x = 0

You create a variable x and set it to 0.

This will store the running total (sum) of numbers.

for i in range(1, 51):

range(1, 51) generates numbers starting from 1 up to 50 (Python excludes the last number).

So it gives: 1, 2, 3, ..., 50.

The loop will run 50 times, and in each turn i takes one of those values.

x += i

This is shorthand for x = x + i.

Each time the loop runs, the value of i is added to x.

So after the first step: x = 0 + 1 = 1,

after the second step: x = 1 + 2 = 3,

after third: x = 3 + 3 = 6,

… and so on until i = 50.

print("The sum of number from 1 to 50 is: ", x)

After the loop finishes, x contains the total sum of numbers from 1 to 50.

The program prints the final result.

