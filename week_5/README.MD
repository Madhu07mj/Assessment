#  Week 5 Assessment

##  Section 1: Multiple Choice Questions

### 1. **Which of the following is used to open a file for reading in Python?**
- A. open('file.txt', 'r')
- B. open('file.txt', 'w')
- C. open('file.txt', 'a')
- D. open('file.txt', 'x')

  Answer: A. open('file.txt', 'r')

### 2. **What method is used to read all lines from a file into a list?** 
- A. read()
- B. readline()
- C. readlines()
- D. readfile()

  Answer: C. readlines()

### 3. **Which function is used to install external Python libraries?** 
- A. get
- B. request
- C. pip
- D. import

  Answer: C. pip

### 4. **What keyword is used to define a class in Python?** 
- A. function
- B. def
- C. struct
- D. class

  Answer: D. class

### 5. **What is the correct method name for object initialization in a class?** 
- A. `__create__`
- B. `__init__`
- C. `constructor()`
- D. `init()`

  Answer: B. __init__

### 6. **Which of the following will write data to a file and overwrite existing content?** 
- A. open('file.txt', 'a')
- B. open('file.txt', 'r')
- C. open('file.txt', 'x')
- D. open('file.txt', 'w')

  Answer: D. open('file.txt', 'w')

### 7. **Which module is used to work with CSV files in Python?** 
- A. os
- B. json
- C. csv
- D. file

  Answer: C. csv

### 8. **Which method in unittest module is used to check if two values are equal?** 
- A. assertSame()
- B. assertEqual()
- C. assertTrue()
- D. assertCompare()

  Answer: B. assertEqual()

### 9. **In requests module, which method is used to send a POST request?** 
- A. requests.fetch()
- B. requests.get()
- C. requests.post()
- D. requests.send()

  Answer: C. requests.post()

### 10. **What is the output of `type([])`?** 
- A. <class 'list'>
- B. <class 'tuple'>
- C. <class 'dict'>
- D. <class 'set'>

  Answer: A. <class 'list'>

### 11. **Which method is called when an object is deleted in Python?** 
- A. `__remove__`
- B. `__del__`
- C. `__destroy__`
- D. `__delete__`

  Answer: B. __del__

### 12. **What is the correct way to write a dictionary to a JSON file?** 
- A. json.write(file, dict)
- B. file.write(json(dict))
- C. json.dump(dict, file)
- D. file.dump(dict, json)

  Answer: C. json.dump(dict, file)


### 13. **Which access modifier is used for private members in Python?** 
- A. _
- B. __
- C. private
- D. protect

  Answer: B. __


### 14. **How do you handle setup and teardown in unittest?** 
- A. init() and destroy()
- B. start() and stop()
- C. setUp() and tearDown()
- D. begin() and end()

  Answer: C. setUp() and tearDown()

### 15. **Which request method is used to fetch data from a REST API?** 
- A. GET
- B. POST
- C. PUT
- D. PATCH

  Answer: A. GET

### 16. **What is the result of `open('file.txt', 'w+').read()` if file exists?**
- A. FileNotFoundError
- B. File content
- C. ''
- D. None

  Answer: C. ''

### 17. **Which of the following best describes method resolution order (MRO)?** 
- A. The order in which methods are compiled
- B. The order of method inheritance in multiple inheritance
- C. The order classes are defined
- D. None of the above

  Answer: B. The order of method inheritance in multiple inheritance

### 18. **What is the result of `json.loads('{"a":1, "b":2}')['c']`?** 
- A. KeyError
- B. None
- C. 'c'
- D. 0

  Answer: A. KeyError

### 19. **Which of these methods from `unittest.TestCase` checks if a statement raises an error?** 
- A. assertRaises()
- B. assertThrows()
- C. expectError()
- D. assertFail()

  Answer: A. assertRaises()

### 20. **Which method is used internally to return a string representation of an object?** 
- A. `__str__`
- B. `__repr__`
- C. `__display__`
- D. `__show__`

  Answer: A. __str__

---

##  Section 2: Coding Questions

1.  Write a Python function that reads a file and prints its content.

2.  Write a class `Rectangle` with `length` and `width`, and a method to calculate area. Create an object and show usage.

3.  Write a unit test using `unittest` module to test a function `add(a, b)` that returns the sum of two numbers.

---