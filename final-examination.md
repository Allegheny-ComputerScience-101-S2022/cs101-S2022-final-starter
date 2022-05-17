# Final Examination for Computer Science 101 Spring 2022

## Table of Contents

**IMPORTANT**: This is the table of contents that was designed to allow you to
navigate between questions if you view this file in your web browser. Please do
not answer the questions in the table of contents.

## Add Your Name Here

**IMPORTANT**: If you do not delete the phrase "Add Your Name Here" and then
type your name in the section header then you are not fully taking credit for
the work that you submitted when completing the examination.

## Re-type the sentence "I adhered to the Allegheny College Honor Code while completing this examination."

You must retype the sentence here.

**IMPORTANT:** If you do not type the required sentence then the course
instructor will not know that you adhered to the Allegheny College Honor Code
while completing the examination.

## Dates for the Final Examination

- **Examination Released**: 2:00 PM on Wednesday, May 18, 2022
- **Examination Due**: 5:00 PM on Wednesday, May 18, 2022

## Honor Code for the Final Examination

- You **must** adhere to the Honor Code throughout your completion of the examination
- You **may use** your laptop computer and its text editor and Python programming tools
- You **may not** refer to the Python source code that you wrote during the semester
- You **may not** refer to the technical writing that you completed during the semester
- You **may not** refer to your notes, the course textbook or web site, or any online resources
- You **may not** discuss any aspect of the examination with anyone except the course instructor

**IMPORTANT**: All students in this course are obligated to adhere to the
Allegheny College Honor Code throughout the completion of this examination. If
the instructor detects that a student has committed a likely violation of the
Allegheny College Honor Code, then he will file a report with the Dean of
Students Office and furnish all details of the likely violation. Please make
sure that you review the [Allegheny College Honor
Code](https://sites.allegheny.edu/about/honor-code/) before you start to take
this examination.

## Procedures for the Final Examination

- You must provide answers to all these questions by typing in this file
- The final version of this file must be in your GitHub repository by the due date
- Unless you make special arrangements with the instructor, no late work will be accepted

## Structure of the Final Examination

- The examination is worth 100 points
- Each question has an assigned point total given in parentheses
- Provide your answer to a question by typing below the subsection header

## Questions for the Final Examination

### (10 Points) Provide a definition of the following features of the Python programming language:

Your response to each of these sub-questions should **give at least one
concrete example** to illustrate your definition. Your response to each of
these sub-questions should also use Python source code in a fenced code block.

**IMPORTANT:** Do not search on the Internet or look in the textbook for the
definition of these terms. You should provide responses to these questions in
your own words, providing source code examples in fenced code blocks as needed.

#### (2 Points) Exception handling in the Python programming language

**IMPORTANT**: Explain the purpose of the `try` and `except` blocks in the
Python programming language and give a source code example of their use.

#### (2 Points) Type annotations in the Python programming language

**IMPORTANT**: Explain the benefits and drawbacks of type annotations in Python
and give a source code example of how they are used in a Python function.

#### (2 Points) `self` parameter in the Python programming language

**IMPORTANT**: Define the `self` parameter and give a concrete source code
example of how it is used during object-oriented programming in Python.

#### (2 Points) Memoization in the Python programming language

**IMPORTANT**: Define the term memoization and give a concrete source code
example of how to implement it in the Python programming language.

#### (2 Points) Sorting algorithm in the Python programming language

**IMPORTANT**: Define the concept of a sorting algorithm and give a concrete
source code example of how to use one in the Python programming language.

### (10 Points) Answer the following questions about the provided source code segment

```python
x = int(input("Enter integer greater than 2: "))
sm_div = None
for guess in range(2, x):
    if x % guess == 0:
        sm_div = guess
        break
if sm_div != None:
    print(f"Smallest divisor of {x} is {sm_div}")
else:
    print(f"Wow, {x} is a prime number!")
```

**IMPORTANT:** Do not search on the Internet or look in the textbook or on the
course web site for the description of this source code. You should provide
responses to each of these questions in your own words, providing supporting
source code examples in fenced code blocks as needed.

#### (2 Points) What is the meaning of the notation `range(2, x)`?

#### (2 Points) What is the purpose of the `if x % guess == 0` statement in this source code?

#### (2 Points) What is an example of an input that will cause the program to execute the first `print` statement? Explain in detail why.

#### (2 Points) What is an example of an input that will cause the program to execute the second `print` statement? Explain in detail why.

#### (2 Points) What is the meaning of the `{x}` notation inside of this source code segment?

### (10 Points) Answer the following questions about the `square` and `call_twice` functions

```python
def apply_to_each(L, f):
    for i in range(len(L)):
        L[i] = f(L[i])

values = [1, -2, 3.33]
print("values =", values)
apply_to_each(values, abs)
print("abs(values) =", values)
apply_to_each(values, int)
print("int(values) =", values)
apply_to_each(values, lambda x: x**2)
print("square(values) =", values)
```

**IMPORTANT:** Do not search on the Internet or look in the textbook our the
course web site for a description of this source code segment. Your answers to
these questions should feature your own words and your own understanding of the
provided segment of Python source code.

#### (4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

**IMPORTANT**: Please provide an answer to this question in a fenced code block.

#### (2 Points) What is the purpose of the source code segment `range(len(L))`?

#### (2 Points) What is the purpose of the source code segment `def apply_to_each(L, f):`?

#### (2 Points) What is the purpose of the source code segment `apply_to_each(values, lambda x: x**2)`?

### (5 Points) Answer the following questions about the provided Python source code segment

```python
for i in range(20):
    print("Value of i: " + str(i))

print()

for i in range(20):
    print("2 to the " + str(i)
          + " power is " + str(2**i))

print()
```

**IMPORTANT:** Do not search on the Internet or look in the textbook or the
course web site for a description of this source code segment. Your answers to
these questions should feature your own words and your own understanding of the
provided segment of Python source code.

#### (2 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

**IMPORTANT**: Please provide an answer to this question in a fenced code block.

#### (1 Points) What is the purpose of the source code segment `range(20)`?

#### (1 Points) What is the purpose of the source code segment `str(i)`?

#### (1 Points) What is the purpose of the source code segment `str(2**i)`?

### (3 Points) Answer the following questions about the provided Python source code segment

```python
def fibonacci_generator(n: int) -> Iterator[int]:
    a = 1
    b = 1
    for i in range(n):
        yield a
        a, b = b, a + b

for fibonacci_value in fibonacci_generator(10):
    print(fibonacci_value, end=" ")
```

**IMPORTANT:** Do not search on the Internet or look in the textbook our the
course web site for a description of this source code segment. Your answers to
these questions should feature your own words and your own understanding of the
provided segment of Python source code.

#### (1 Points) What is the purpose of the source code segment `a, b = b, a + b`?

#### (1 Points) What is the purpose of the source code segment `yield a`?

#### (1 Points) What is the purpose of the source code segment `for i in range(n):`?

### (10 Points) Using a fenced code block, provide the requested Python functions

**IMPORTANT:** Do not search on the Internet or look in the textbook for the way
to implement the requested functions. You should provide the requested source
code while only leveraging your own creativity and technical expertise.

#### (5 Points) A Python function called `compute_intersection` that accepts as input two tuples and returns a tuple of the elements that those tuples have in common

#### (5 Points) A Python function called `linear_search` that takes a `list` called `L` and an `int` called `e` as input and returns a `bool` indicating whether the element `e` is contained in the list `L`

### (10 Points) Answer the following questions about the provided Python source code segment and the `fibonacci_recursive` function

```python
def fibonacci_recursive(n: int) -> int:
    if n == 0 or n == 1:
        return 1
    else:
        return fibonacci_recursive(n-1) + fibonacci_recursive(n-2)

for i in range(10):
    print(f"fib of {i} is {fibonacci_recursive(i)}")
```

**IMPORTANT:** Do not search on the Internet or look in the textbook our the
course web site for a description of this source code segment. Your answers to
these questions should feature your own words and your own understanding of the
provided segment of Python source code.

#### (4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

**IMPORTANT**: Please provide an answer to this question in a fenced code block.

#### (6 Points) Using extensive detail, please explain the following components of `fibonacci_recursive`

##### (2 Points) The **base case** of the function

##### (2 Points) The **recursive case** of the function

##### (2 Points) Evidence that the function **makes progress to the base case**

### (10 Points) Answer the following questions about optimization problems using the following table that describes an instance of the 0/1 knapsack problem

```
| Item     | Value | Weight | Value/Weight |
|--------  |-------|--------|--------------|
| Clock    | 175   |   10   |   17.5       |
| Painting | 90    |   9    |   10         |
| Radio    | 20    |   4    |   5          |
| Vase     | 50    |   2    |   25         |
| Book     | 10    |   1    |   10         |
| Computer | 200   |   20   |   10         |
```

#### (2 Points) The 0/1 knapsack problem is an example of an optimization problem. What is an optimization problem?

#### (4 Points) How would a greedy-by-density (also called greedy-by-ratio) algorithm solve this instance of the 0/1 knapsack problem?

**IMPORTANT**: In addition to explaining how this algorithm works, your response
to this question should provide the output of the algorithm given the provided
table of six items.

#### (4 Points) How would exhaustive enumeration algorithm solve this instance of the 0/1 knapsack problem?

**IMPORTANT**: In addition to explaining how this algorithm works, your response
to this question should provide the output of the algorithm given the provided
table of six items.

### (10 Points) Define the following terms and activities related to software testing and debugging

**IMPORTANT**: Do not look up definitions for these terms in your textbook or an
online source. You should provide your own response to these questions in your
own words without consulting any external resources.

#### (2 Points) What is the purpose of software testing?

#### (2 Points) What does a tester do when performing closed-box testing?

#### (2 Points) What does a tester do when performing glass-box testing

#### (2 Points) What steps would you take to use testing to ensure that a hashtable (i.e., dictionary) was implemented correctly?

#### (2 Points) What steps would you take to use testing to ensure that a sorting algorithm was implemented correctly?

### (2 Points) Identify and explain the two defects inside of the following constructor for a dictionary

```python
def __str__(self, num_buckets: int) -> None:
    self.buckets = None
    self.num_buckets = num_buckets
    for i in range(num_buckets):
        self.buckets.append([])
```

- What is the first defect in the constructor for a dictionary?

- What is the second defect in the constructor for a dictionary?

### (12 Points) Answer the following questions about the structured types provided by the Python programming language

**IMPORTANT**: Use Python source code to provide each of the requested examples.

#### (3 Points) The `str` structured type

##### Give an example of each of the characteristics of this structured type

**IMPORTANT**: Use Python source code to provide each of the requested examples.
You should place each of your examples below the prompt in the list. Please
remember to provide three examples in total in your response to this question.

- An empty `str`
- A singleton `str`
- A `str` that contains many elements

#### (3 Points) The `list` structured type

##### Give an example of each of the characteristics of this structured type

**IMPORTANT**: Use Python source code to provide each of the requested examples.
You should place each of your examples below the prompt in the list. Please
remember to provide three examples in total in your response to this question.

- An empty `list`
- A singleton `list`
- A `list` that contains many elements

#### (3 Points) The `tuple` structured type

##### Give an example of each of the characteristics of this structured type

**IMPORTANT**: Use Python source code to provide each of the requested examples.
You should place each of your examples below the prompt in the list. Please
remember to provide three examples in your response to this question.

- An empty `tuple`
- A singleton `tuple`
- A `tuple` that contains many elements

### (5 Points) Provide a detailed response that explains the worst-case time complexity of the provided Python function

```python
def fact(n):
  """Assumes n is a positive int. Returns the value of n!."""
  answer = 1
  while n > 1:
    answer *= n
    n -= 1
  return answer
```

#### (2 points) Using the Big-O notation, what is the worst-case time time complexity of this function? Please show all of your work.

#### (2 points) Using your knowledge of running a doubling experiment to predict the likely worst-case time complexity, about what would the doubling ratio be for this function?

#### (1 points) Using your knowledge of the Big-O notation, would you describe this as an efficient algorithm? Why?

### (3 Points) For each scenario, compute the doubling ratio and then suggest the likely worst-case time complexity

#### (1 point) Original size of the data has a running time of 11.23 seconds and doubled size of data has running time of 89.72 seconds

- What is the doubling ratio?
- What is the likely worst-case time complexity?

#### (1 point) Original size of the data has a running time of 14.98 seconds and doubled size of data has running time of 31.45 seconds

- What is the doubling ratio?
- What is the likely worst-case time complexity?

#### (1 point) Original size of the data has a running time of 12.63 seconds and doubled size of data has running time of 51.48 seconds

- What is the doubling ratio?
- What is the likely worst-case time complexity?
