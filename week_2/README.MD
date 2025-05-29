# Week 2 Assessment

## Section 1: Multiple Choice Questions


1. **What is the output of `list(map(lambda x: x*2, [1,2,3]))`?**

   A. [2,4,6]

   B. [1,2,3]

   C. [1,4,9]

   D. Error

   Answer: A. [2, 4, 6]



2. **Which keyword is used to create a generator function?**

   A. gen

   B. yield

   C. return

   D. def

   Answer: B. yield



3. **What will be the output of: `def func(x=1): return x + 1; print(func())`?** 

   A. 1

   B. 2

   C. None

   D. Error

   Answer: B. 2



4. **Which function is used to reduce a list to a single value?**

   A. filter()

   B. map()

   C. reduce()

   D. zip()

   Answer: C. reduce()



5. **Which is NOT a Python built-in data type?**

   A. list

   B. tuple

   C. array

   D. set

   Answer: C. array



6. **What is the result of `filter(lambda x: x%2==0, [1,2,3,4])`?**

   A. [1,3]

   B. [2,4]

   C. [1,2,3,4]

   D. [2]

   Answer: B. [2, 4]



7. **What will be printed: `a = [1,2,3]; b = iter(a); print(next(b))`?** 

   A. 1

   B. 2

   C. 3

   D. Error

   Answer: A. 1



8. **Which function combines two lists into tuples?**

   A. map()

   B. zip()

   C. filter()

   D. enumerate()

   Answer: B. zip()



9. **What is the result of `sum(map(len, ['ab', 'cde']))`?**

   A. 3

   B. 5

   C. 6

   D. Error

   Answer: B. 5



10. **Which of the following is a decorator syntax in Python?**

    A. #decorator

    B. @decorator

    C. *decorator

    D. &decorator

    Answer: B. @decorator



11. **What happens if a function decorated by a decorator does not return a value?**

    A. Returns None

    B. Raises an error

    C. The original function runs

    D. Skips execution

    Answer: A. Returns None



12. **What is the output of `(lambda x: x**2)(3)`?**

    A. 6

    B. 9

    C. 3

    D. Error

    Answer: B. 9



13. **What is the output of `list(enumerate(['a','b']))`?**

     A. [(0, 'a'), (1, 'b')]

     B. [('a',0), ('b',1)]

     C. ['a', 'b']

     D. Error

     Answer: A. [(0, 'a'), (1, 'b')]



14. **Which of these statements is True about recursion?**

    A. Recursion always terminates

    B. Recursion can replace loops

    C. Recursion cannot be used in Python

    D. Recursion requires no base case

    Answer: B. Recursion can replace loops



15. **Which of these returns an iterator object?**

    A. list()

    B. iter()

    C. tuple()

    D. dict()

    Answer: B. iter()



16. **What will be the output of this code:**

```bash

def foo():
    yield 1
    return 2
x = list(foo())
print(x)

```

    A. [1,2]

    B. [1]

    C. [2]

    D. Error

    Answer: B. [1]



17. **Which of the following is NOT True for lambda functions?**

    A. They can have multiple expressions

    B. They can be assigned to a variable

    C. They return a function object

    D. They can be used as arguments

    Answer: A. They can have multiple expressions



18. **What is the output of this code:

```bash
a = [1,2,3]
b = map(lambda x: x+1, a)
print(list(b))
print(list(b))

```
    A. [2,3,4] [2,3,4]

    B. [2,3,4] []

    C. [] []

    D. Error

    Answer: B. [2, 3, 4] []



19. **Which of these is a side effect of using recursion?**

    A. Increased performance

    B. Reduced stack depth

    C. Stack overflow risk

    D. Memory leak

    Answer: C. Stack overflow risk



20. **Which of the following about decorators is correct?**

    A. Decorators must always return the original function

    B. Decorators cannot modify arguments

    C. Decorators are applied at runtime

    D. Decorators are applied at function definition

    Answer: D. Decorators are applied at function definition
