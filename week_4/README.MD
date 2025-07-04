#  Week 4 Assessment 

##  Section 1: Multiple Choice Questions


1. **Which Python function is used to loop with index and value together?** 

   A. range()

   B. zip()

   C. enumerate()

   D. list()

   Answer: C. enumerate()




2. **What is the output of: `f"Value is {5}"`?**

   A. Value is 5

   B. fValue is 5

   C. Error

   D. {5}

   Answer: A. Value is 5

3. **Which of the following is a valid list comprehension?** 

   A. [x in range(5)]

   B. [x for x in range(5)]

   C. for x in range(5):

   D. list x in range(5)

   Answer: B. [x for x in range(5)]


4. **What is the correct comment symbol in Python?**

   A. //

   B. <!-- -->

   C. #

   D. /**/

   Answer: C. #


5. **Which of the following is used to specify a type hint for an integer?** 

   A. int()

   B. type=int

   C. -> int

   D. as int

   Answer: C. -> int

6. **What will be the output of: `list(zip([1, 2], ['a', 'b']))`?** 

   A. [(1, 'a'), (2, 'b')]

   B. [(1, 2), ('a', 'b')]

   C. [[1, 'a'], [2, 'b']]

   D. Error

   Answer: A. [(1, 'a'), (2, 'b')]

7. **What is the output of: `[x**2 for x in range(3)]`?**

   A. [0, 1, 2]

   B. [1, 4, 9]

   C. [0, 1, 4]

   D. [0, 2, 4]

   Answer: C. [0, 1, 4]

8. **Which tool checks Python code style against PEP8?** 

   A. PyTest

   B. Flake8

   C. PyLint

   D. Black

   Answer: B. Flake8

9. **Which syntax shows a lambda function to square a number?** 

   A. lambda x: x**2

   B. x => x*x

   C. def x(x): return x*x

   D. map(x): return x^2

   Answer: A. lambda x: x**2

10. **What is the purpose of type hints in Python?** 

    A. Compile time type enforcement

    B. Runtime type enforcement

    C. Optional static typing for readability/tools

    D. None

    Answer: C. Optional static typing for readability/tools

11. **What is the output of: `list(enumerate(['a', 'b']))`?**

    A. [(0, 'a'), (1, 'b')]

    B. [('a', 0), ('b', 1)]

    C. ['a', 'b']

    D. Error

    Answer: A. [(0, 'a'), (1, 'b')]

12. **Which statement about list comprehensions is TRUE?**

    A. They are always faster than loops

    B. They replace all loops

    C. They create a new list using an expression and iteration

    D. They are deprecated

    Answer: C. They create a new list using an expression and iteration

13. **Which of the following will raise a syntax error in a comprehension?** 

    A. [x for x in range(5)]

    B. [x for x in 5]

    C. [x*x for x in range(5)]

    D. list(x for x in range(5))

    Answer: B. [x for x in 5]

14. **Which Python library can be configured for custom linting rules?** 

    A. Black

    B. PyTest

    C. PyLint

    D. MyPy

    Answer: C. PyLint


15. **What is the output of: `f"{2+2} equals four"`?** 

    A. 2+2 equals four

    B. four equals 4

    C. 4 equals four

    D. Error

    Answer: C. 4 equals four

16. **What does this comprehension produce: `{x: x**2 for x in range(3)}`?** 

    A. [0, 1, 4]

    B. {0, 1, 4}

    C. {0: 0, 1: 1, 2: 4}

    D. (0, 1, 4)

    Answer: C. {0: 0, 1: 1, 2: 4}

17. **What is the type of result: `type([x for x in 'abc'])`?** 

    A. <class 'str'>

    B. <class 'list'>

    C. <class 'tuple'>

    D. <class 'dict'>

    Answer: B. <class 'list'>

18. **Which of the following is most Pythonic to reverse a list?** 

    A. for i in reversed(list):

    B. list[::-1]

    C. list.reverse()

    D. All of the above

    Answer: D. All of the above

19. **What happens if PyLint sees a function without a docstring?** 

    A. Skips it

    B. Adds warning

    C. Crashes

    D. Auto-generates doc

    Answer: B. Adds warning

20. **Which of the following uses type hint for a function returning a float?**

    A. def add(x, y): float

    B. def add(x, y) -> float:
   
    C. def add: float

    D. def add(x, y) => float:

    Answer: B. def add(x, y) -> float:

---

##  Section 2: Coding Questions

1.  Write a list comprehension to generate a list of squares from 1 to 10.

```
Example 1:
Input: Range = 1 to 10
Output: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

Example 2:
Input: Range = 1 to 5
Output: [1, 4, 9, 16, 25]

Example 3:
Input: Range = 3 to 6
Output: [9, 16, 25, 36]
```

2.  Write a function that takes a list of numbers and returns their sum using enumerate (do not use sum()).

```
Example 1:
Input: [1, 2, 3, 4]
Output: 10

Example 2:
Input: [5, 10, 15]
Output: 30

Example 3:
Input: [-1, 0, 1]
Output: 0
```
3.  Write a function that takes another function and returns a new function that logs input and output using decorators and f-strings.

```
Example 1:
Input: logged_add([3, 5])
Output: 8

Example 2:
Input: logged_concat(["Hello", "World"])
Output: "HelloWorld"

Example 3:
Input: logged_multiply([4, 2])
Output: 8

```

---
