# Python Loops
In Python, loops are used to execute a set of instructions repeatedly. There are two types of loops in Python: for loop and while loop.

## For Loop
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string). 
With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.

``` 
for variable in sequence:
# statements to be executed for each element in sequence
```
Here, variable represents the current element in the sequence, and sequence is the collection of elements to be iterated over.
For example, let's say you have a list of numbers and you want to print each number in the list:

```
numbers = [1, 2, 3, 4, 5]

for number in numbers:
    print(number)
1
2
3
4
5
```

## While Loop
The while loop is used to execute a block of code as long as a certain condition is true. Here's the basic syntax of a while loop:

```
while condition:
# statements to be executed as long as condition is true
```
Here, condition is the expression that is evaluated to determine whether the loop should continue or not.
For example, let's say you want to print all the even numbers between 0 and 10:

```
 = 0

while i <= 10:
    if i % 2 == 0:
        print(i)
    i += 1

0
2
4
6
8
10
```

In this example, the loop continues as long as i is less than or equal to 10. 
The if statement checks whether the current value of i is even, and if it is, it prints the value. 
Finally, the loop increments the value of i by 1 on each iteration.


## Nested Loop

Python allows you to create nested loops, which are loops that are placed inside another loop. 
This is useful when you need to perform repetitive tasks on nested data structures such as nested lists, dictionaries or tuples.

Here's an example of a nested for loop that iterates over a list of lists:

```
matrix = [[1, 2, 3],
          [4, 5, 6],
          [7, 8, 9]]

for row in matrix:
    for item in row:
        print(item, end=' ')
    print()
```

In this example, the outer loop iterates over each list in the matrix, while the inner loop iterates over each item in each list. 
The print() statement with no argument is used to move the output to the next line after each row has been printed.

Here's an example of a nested while loop that calculates the product of all pairs of numbers between 1 and 5:

```
i = 1
while i <= 5:
    j = 1
    while j <= 5:
        product = i * j
        print(product, end=' ')
        j += 1
    print()
    i += 1
```

In this example, the outer loop counts from 1 to 5, while the inner loop also counts from 1 to 5. 
The product of i and j is calculated in each iteration of the inner loop, and printed to the console. 
The print() statement with no argument is used to move the output to the next line after each row has been printed.
