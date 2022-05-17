# Final Examination for Computer Science 101 Spring 2022

## Table of Contents

**IMPORTANT**: This is the table of contents that was designed to allow you to
navigate between questions if you view this file in your web browser. Please do
not answer the questions in the table of contents.

* [Questions for the Final Examination](#questions-for-the-final-examination)
  + [(10 Points) Provide a definition of the following features of the Python programming language:](#10-points-provide-a-definition-of-the-following-features-of-the-python-programming-language)
    - [(2 Points) Exception handling in the Python programming language](#2-points-exception-handling-in-the-python-programming-language)
    - [(2 Points) Type annotations in the Python programming language](#2-points-type-annotations-in-the-python-programming-language)
    - [(2 Points) `self` parameter in the Python programming language](#2-points-self-parameter-in-the-python-programming-language)
    - [(2 Points) Memoization in the Python programming language](#2-points-memoization-in-the-python-programming-language)
    - [(2 Points) Sorting algorithm in the Python programming language](#2-points-sorting-algorithm-in-the-python-programming-language)
  + [(10 Points) Answer the following questions about the provided source code segment](#10-points-answer-the-following-questions-about-the-provided-source-code-segment)
    - [(2 Points) What is the meaning of the notation `range(2, x)`?](#2-points-what-is-the-meaning-of-the-notation-range2-x)
    - [(2 Points) What is the purpose of the `if x % guess == 0` statement in this source code?](#2-points-what-is-the-purpose-of-the-if-x-%25-guess--0-statement-in-this-source-code)
    - [(2 Points) What is an example of an input that will cause the program to execute the first `print` statement? Explain in detail why.](#2-points-what-is-an-example-of-an-input-that-will-cause-the-program-to-execute-the-first-print-statement-explain-in-detail-why)
    - [(2 Points) What is an example of an input that will cause the program to execute the second `print` statement? Explain in detail why.](#2-points-what-is-an-example-of-an-input-that-will-cause-the-program-to-execute-the-second-print-statement-explain-in-detail-why)
    - [(2 Points) What is the meaning of the `{x}` notation inside of this source code statement?](#2-points-what-is-the-meaning-of-the-x-notation-inside-of-this-source-code-statement)
  + [(10 Points) Answer the following questions about the `square` and `call_twice` functions](#10-points-answer-the-following-questions-about-the-square-and-call_twice-functions)
    - [(4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?](#4-points-what-is-the-exact-output-including-blank-lines-and-spaces-of-the-provided-source-code-segment)
    - [(2 Points) What is the purpose of the source code segment `len(L)`?](#2-points-what-is-the-purpose-of-the-source-code-segment-lenl)
    - [(2 Points) What is the purpose of the source code segment `def apply_to_each(L, f):`?](#2-points-what-is-the-purpose-of-the-source-code-segment-def-apply_to_eachl-f)
    - [(2 Points) What is the purpose of the source code segment `values = [1, -2, 3.33]`?](#2-points-what-is-the-purpose-of-the-source-code-segment-values--1--2-333)
  + [(10 Points) Answer the following questions about the provided Python source code segment](#10-points-answer-the-following-questions-about-the-provided-python-source-code-segment)
    - [(4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?](#4-points-what-is-the-exact-output-including-blank-lines-and-spaces-of-the-provided-source-code-segment-1)
    - [(2 Points) What is the purpose of the source code segment `range(20)`?](#2-points-what-is-the-purpose-of-the-source-code-segment-range20)
    - [(2 Points) What is the purpose of the source code segment `str(i)`?](#2-points-what-is-the-purpose-of-the-source-code-segment-stri)
    - [(2 Points) What is the purpose of the source code segment `str(2**i)`?](#2-points-what-is-the-purpose-of-the-source-code-segment-str2i)
  + [(10 Points) Using a fenced code block, provide the requested Python functions](#10-points-using-a-fenced-code-block-provide-the-requested-python-functions)
    - [(5 Points) A Python function called `compute_intersection` that accepts as input two tuples and returns a tuple of the elements that those tuples have in common](#5-points-a-python-function-called-compute_intersection-that-accepts-as-input-two-tuples-and-returns-a-tuple-of-the-elements-that-those-tuples-have-in-common)
    - [(5 Points) A Python function called `linear_search` that takes a `list` called `L` and an `int` called `e` as input and returns a `bool` indicating whether the element `e` is contained in the list `L`](#5-points-a-python-function-called-linear_search-that-takes-a-list-called-l-and-an-int-called-e-as-input-and-returns-a-bool-indicating-whether-the-element-e-is-contained-in-the-list-l)
  + [(10 Points) Answer the following questions about the provided Python source code segment and the `fibonacci_recursive` function](#10-points-answer-the-following-questions-about-the-provided-python-source-code-segment-and-the-fibonacci_recursive-function)
    - [(4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?](#4-points-what-is-the-exact-output-including-blank-lines-and-spaces-of-the-provided-source-code-segment-2)
    - [(6 Points) Using extensive detail, please explain the following components of `fibonacci_recursive`](#6-points-using-extensive-detail-please-explain-the-following-components-of-fibonacci_recursive)
      * [(2 Points) The **base case** of the function](#2-points-the-base-case-of-the-function)
      * [(2 Points) The **recursive case** of the function](#2-points-the-recursive-case-of-the-function)
      * [(2 Points) Evidence that the function **makes progress to the base case**](#2-points-evidence-that-the-function-makes-progress-to-the-base-case)
  + [(10 Points) Answer the following questions about optimization problems using the following table that describes an instance of the 0/1 knapsack problem](#10-points-answer-the-following-questions-about-optimization-problems-using-the-following-table-that-describes-an-instance-of-the-01-knapsack-problem)
    - [(2 Points) The 0/1 knapsack problem is an example of an optimization problem. What is an optimization problem?](#2-points-the-01-knapsack-problem-is-an-example-of-an-optimization-problem-what-is-an-optimization-problem)
    - [(4 Points) How would a greedy-by-density algorithm solve this instance of the 0/1 knapsack problem?](#4-points-how-would-a-greedy-by-density-algorithm-solve-this-instance-of-the-01-knapsack-problem)
    - [(4 Points) How would exhaustive enumeration algorithm solve this instance of the 0/1 knapsack problem?](#4-points-how-would-exhaustive-enumeration-algorithm-solve-this-instance-of-the-01-knapsack-problem)
  + [(10 Points) Define the following terms and activities related to software testing and debugging](#10-points-define-the-following-terms-related-to-software-testing-and-debugging)
    - [(2 Points) What is the purpose of software testing?](#2-points-what-is-the-purpose-of-software-testing)
    - [(2 Points) Closed-box testing](#2-points-closed-box-testing)
    - [(2 Points) Glass-box testing](#2-points-glass-box-testing)
    - [(2 Points) What steps would you take to use testing to ensure that a hashtable (i.e., dictionary) was implemented correctly?](#2-points-what-steps-would-you-take-to-use-testing-to-ensure-that-a-hashtable-ie-dictionary-was-implemented-correctly)
    - [(2 Points) What steps would you take to use testing to ensure that a sorting algorithm was implemented correctly?](#2-points-what-steps-would-you-take-to-use-testing-to-ensure-that-a-sorting-algorithm-was-implemented-correctly)
  + [(12 Points) Answer the following questions about the structured types provided by the Python programming language](#12-points-answer-the-following-questions-about-the-structured-types-provided-by-the-python-programming-language)
    - [(3 Points) The `str` structured type](#3-points-the-str-structured-type)
      * [Give an example of each of the characteristics of this structured type](#give-an-example-of-each-of-the-characteristics-of-this-structured-type)
    - [(3 Points) The `list` structured type](#3-points-the-list-structured-type)
      * [Give an example of each of the characteristics of this structured type](#give-an-example-of-each-of-the-characteristics-of-this-structured-type-1)
    - [(3 Points) The `tuple` structured type](#3-points-the-tuple-structured-type)
      * [Give an example of each of the characteristics of this structured type](#give-an-example-of-each-of-the-characteristics-of-this-structured-type-2)
* [(8 Points) Provide a detailed response that explains the worst-case time complexity of the provided Python function](#8-points-provide-a-detailed-response-that-explains-the-worst-case-time-complexity-of-the-provided-python-function)
  + [(4 points) Using the Big-O notation, what is the worst-case time time complexity of this function? Please show all of your work.](#4-points-using-the-big-o-notation-what-is-the-worst-case-time-time-complexity-of-this-function-please-show-all-of-your-work)
  + [(2 points) Using your knowledge of running a doubling experiment to predict the likely worst-case time complexity, about what would the doubling ratio be for this function?](#2-points-using-your-knowledge-of-running-a-doubling-experiment-to-predict-the-likely-worst-case-time-complexity-about-what-would-the-doubling-ratio-be-for-this-function)
  + [(2 points) Using your knowledge of the Big-O notation, would you describe this as an efficient algorithm? Why?](#2-points-using-your-knowledge-of-the-big-o-notation-would-you-describe-this-as-an-efficient-algorithm-why)

### Add Your Name Here

**IMPORTANT**: If you do not delete the phrase "Add Your Name Here" and then
type your name in the section header then you are not fully taking credit for
the work that you submitted when completing the examination.

### Re-type the sentence "I adhered to the Allegheny College Honor Code while completing this examination."

You must retype the sentence here.

**IMPORTANT:** If you do not type the required sentence then the course
instructor will not know that you adhered to the Allegheny College Honor Code
while completing the examination.

### Dates for the Final Examination

- **Examination Released**: 2:00 PM on Wednesday, May 18, 2022
- **Examination Due**: 5:00 PM on Wednesday, May 18, 2022

### Honor Code for the Final Examination

- You **must** adhere to the Honor Code throughout your completion of the examination
- You **may use** your laptop computer and its text editor and Python programming tools
- You **may not** refer to the Python source code that you wrote during the semester
- You **may not** refer to the technical writing that you completed during the semester
- You **may not** refer to your notes, the course textbook, or any online resources
- You **may not** discuss any aspect of the examination with anyone except the course instructor

**IMPORTANT**: All students in this course are obligated to adhere to the
Allegheny College Honor Code throughout the completion of this examination. If
the instructor detects that a student has committed a likely violation of the
Allegheny College Honor Code, then he will file a report with the Dean of
Students Office and furnish all details of the likely violation. Please make
sure that you review the [Allegheny College Honor
Code](https://sites.allegheny.edu/about/honor-code/) before you start to take
this examination.

### Procedures for the Final Examination

- You must provide answers to all these questions by typing in this file
- The final version of this file must be in your GitHub repository by the due date
- Unless you make special arrangements with the instructor, no late work will be accepted

### Structure of the Final Examination

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

#### (2 Points) What is the meaning of the notation `range(2, x)`?

#### (2 Points) What is the purpose of the `if x % guess == 0` statement in this source code?

#### (2 Points) What is an example of an input that will cause the program to execute the first `print` statement? Explain in detail why.

#### (2 Points) What is an example of an input that will cause the program to execute the second `print` statement? Explain in detail why.

#### (2 Points) What is the meaning of the `{x}` notation inside of this source code statement?

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

#### (4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

Please provide an answer to this question in a fenced code block.

#### (2 Points) What is the purpose of the source code segment `len(L)`?

#### (2 Points) What is the purpose of the source code segment `def apply_to_each(L, f):`?

#### (2 Points) What is the purpose of the source code segment `values = [1, -2, 3.33]`?

### (10 Points) Answer the following questions about the provided Python source code segment

```python
for i in range(20):
    print("Value of i: " + str(i))

print()

for i in range(20):
    print("2 to the " + str(i)
          + " power is " + str(2**i))

print()
```

#### (4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

Please provide an answer to this question in a fenced code block.

#### (2 Points) What is the purpose of the source code segment `range(20)`?

#### (2 Points) What is the purpose of the source code segment `str(i)`?

#### (2 Points) What is the purpose of the source code segment `str(2**i)`?

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

#### (4 Points) What is the exact output (including blank lines and spaces) of the provided source code segment?

Please provide an answer to this question in a fenced code block.

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

#### (4 Points) How would a greedy-by-density algorithm solve this instance of the 0/1 knapsack problem?

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

#### (2 Points) Closed-box testing

#### (2 Points) Glass-box testing

#### (2 Points) What steps would you take to use testing to ensure that a hashtable (i.e., dictionary) was implemented correctly?

#### (2 Points) What steps would you take to use testing to ensure that a sorting algorithm was implemented correctly?

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

## (8 Points) Provide a detailed response that explains the worst-case time complexity of the provided Python function

```python
def fact(n):
  """Assumes n is a positive int. Returns the value of n!."""
  answer = 1
  while n > 1:
    answer *= n
    n -= 1
  return answer
```

### (4 points) Using the Big-O notation, what is the worst-case time time complexity of this function? Please show all of your work.

### (2 points) Using your knowledge of running a doubling experiment to predict the likely worst-case time complexity, about what would the doubling ratio be for this function?

### (2 points) Using your knowledge of the Big-O notation, would you describe this as an efficient algorithm? Why?
