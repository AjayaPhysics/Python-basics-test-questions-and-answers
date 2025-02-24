# Python-basics-test-questions-and-answers
# 📝 Python Basics Test with Answers

---

## 📌 Section A: Multiple Choice Questions (1 Mark Each)  
**[Total: 20 Marks]**

| **No.** | **Question** | **Options** | **Answer** |
|---------|--------------|-------------|------------|
| 1 | Which function is used to display output in Python? | a) print(), b) display(), c) show(), d) output() | a) print() |
| 2 | What symbol is used to start a comment in Python? | a) //, b) /*, c) --, d) # | d) # |
| 3 | Which of the following is a valid variable name? | a) 2variable, b) variable_name, c) variable-name, d) variable name | b) variable_name |
| 4 | Which data type stores a sequence of characters? | a) int, b) float, c) str, d) list | c) str |
| 5 | What is the output of `print(type(10))`? | a) int, b) float, c) str, d) bool | a) int |
| 6 | Keyword to define a function in Python | a) func, b) def, c) define, d) function | b) def |
| 7 | Correct syntax to create a list | a) list=(1,2,3), b) list=[1,2,3], c) list={1,2,3}, d) list=<1,2,3> | b) list=[1,2,3] |
| 8 | Function to take input from the user | a) get(), b) input(), c) read(), d) enter() | b) input() |
| 9 | Operator used to check equality | a) =, b) ==, c) !=, d) === | b) == |
| 10 | Function to find the length of a string/list | a) count(), b) length(), c) len(), d) size() | c) len() |
| 11 | Output of `print(2 ** 3)` | a) 6, b) 8, c) 9, d) 16 | b) 8 |
| 12 | Keyword to exit a loop | a) exit, b) stop, c) break, d) continue | c) break |
| 13 | Function to convert string to lowercase | a) lower(), b) downcase(), c) tolower(), d) casefold() | a) lower() |
| 14 | Create an infinite loop in Python | a) for i in range(infinity), b) while True, c) loop forever(), d) repeat indefinitely | b) while True |
| 15 | Result of `3 + 2 * 2` | a) 10, b) 7, c) 8, d) 9 | b) 7 |
| 16 | Which of the following is mutable? | a) tuple, b) string, c) list, d) integer | c) list |
| 17 | What does `int('10')` return? | a) '10', b) 10.0, c) 10, d) Error | c) 10 |
| 18 | Module for generating random numbers | a) math, b) random, c) numbers, d) randint | b) random |
| 19 | Syntax for function with two parameters | a) def func(a, b), b) def func[a, b], c) def func{a, b}, d) function(a, b) | a) def func(a, b) |
| 20 | Statement to skip to the next iteration of a loop | a) break, b) continue, c) pass, d) skip | b) continue |

---

## ✏️ Section B: Short Answer Questions (4 Marks Each)  
**[Total: 80 Marks]**

| **No.** | **Question** | **Answer** |
|---------|--------------|------------|
| 1 | Define a variable in Python with an example. | A variable is a name that refers to a value. Example: `x = 10` |
| 2 | Explain the difference between a list and a tuple. | A list is mutable, while a tuple is immutable. |
| 3 | Write a program to check if a number is positive, negative, or zero. | ```python\nnum = int(input(\"Enter a number: \"))\nif num > 0: print(\"Positive\")\nelif num < 0: print(\"Negative\")\nelse: print(\"Zero\")\n``` |
| 4 | Use of `input()` with example. | `input()` takes user input as a string. Example: `name = input(\"Enter your name: \")` |
| 5 | Multiplication table of a number. | ```python\nnum = int(input(\"Enter a number: \"))\nfor i in range(1, 11): print(num, \"x\", i, \"=\", num * i)\n``` |
| 6 | Difference between `for` loop and `while` loop. | `for` loop iterates over a sequence; `while` loop repeats until a condition is false. |
| 7 | Largest number among three numbers. | ```python\na, b, c = map(int, input(\"Enter three numbers: \").split())\nprint(max(a, b, c))\n``` |
| 8 | Use of `len()` with examples. | `len()` returns the number of elements or characters. Example: `len([1, 2, 3])` returns 3. |
| 9 | Reverse a string using a loop. | ```python\ntext = input(\"Enter a string: \")\nreversed_text = \"\"\nfor char in text: reversed_text = char + reversed_text\nprint(reversed_text)\n``` |
| 10 | Purpose of `break` and `continue`. | `break` exits a loop, while `continue` skips the current iteration. |
| 11 | Factorial of a number using `for` loop. | ```python\nnum = int(input(\"Enter a number: \"))\nfactorial = 1\nfor i in range(1, num + 1): factorial *= i\nprint(\"Factorial:\", factorial)\n``` |
| 12 | Syntax error and logical error examples. | Syntax error: `if x == 5 print(x)` (missing colon), Logical error: Using wrong formula for average. |
| 13 | Count vowels in a string. | ```python\ntext = input(\"Enter a string: \")\nvowels = \"aeiouAEIOU\"\ncount = sum(1 for char in text if char in vowels)\nprint(\"Number of vowels:\", count)\n``` |
| 14 | Use of `range()` with examples. | `range(start, stop, step)` generates numbers from start to stop-1. Example: `range(1, 6)` produces `[1, 2, 3, 4, 5]` |
| 15 | Check if a string is a palindrome. | ```python\ntext = input(\"Enter a string: \")\nif text == text[::-1]: print(\"Palindrome\")\nelse: print(\"Not a palindrome\")\n``` |
| 16 | Conditional statements with example. | Conditional statements control program flow. Example: `if score >= 50: print(\"Pass\") else: print(\"Fail\")` |
| 17 | Print numbers 1 to 20 using `while` loop. | ```python\nnum = 1\nwhile num <= 20: print(num)\nnum += 1\n``` |
| 18 | Difference between `append()` and `extend()`. | `append()` adds a single element; `extend()` adds all elements from an iterable. |
| 19 | Sum of digits of a number. | ```python\nnum = input(\"Enter a number: \")\nsum_digits = sum(int(digit) for digit in num)\nprint(\"Sum of digits:\", sum_digits)\n``` |
| 20 | Difference between mutable and immutable data types. | Mutable types (e.g., lists) can be changed; immutable types (e.g., strings, tuples) cannot. |

---

# 📝 Python Short Answer Solutions (Easy Copy for VS Code)

| **No.** | **Question** | **Python Code Solution** |
|---------|--------------|--------------------------|
| **3** | Check if a number is positive, negative, or zero | <br>num = int(input(\"Enter a number: \"))<br>if num > 0:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(\"Positive\")<br>elif num < 0:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(\"Negative\")<br>else:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(\"Zero\")<br> |
| **5** | Print multiplication table of a number | <br>num = int(input(\"Enter a number: \"))<br>for i in range(1, 11):<br>&nbsp;&nbsp;&nbsp;&nbsp;print(num, \"x\", i, \"=\", num * i)<br> |
| **7** | Find the largest number among three numbers | <br>a, b, c = map(int, input(\"Enter three numbers separated by spaces: \").split())<br>print(\"Largest number is:\", max(a, b, c))<br> |
| **9** | Reverse a string using a loop | <br>text = input(\"Enter a string: \")<br>reversed_text = \"\"<br>for char in text:<br>&nbsp;&nbsp;&nbsp;&nbsp;reversed_text = char + reversed_text<br>print(\"Reversed string:\", reversed_text)<br> |
| **11** | Calculate factorial using a `for` loop | <br>num = int(input(\"Enter a number: \"))<br>factorial = 1<br>for i in range(1, num + 1):<br>&nbsp;&nbsp;&nbsp;&nbsp;factorial *= i<br>print(\"Factorial of\", num, \"is\", factorial)<br> |
| **13** | Count vowels in a string | <br>text = input(\"Enter a string: \")<br>vowels = \"aeiouAEIOU\"<br>count = sum(1 for char in text if char in vowels)<br>print(\"Number of vowels:\", count)<br> |
| **15** | Check if a string is a palindrome | <br>text = input(\"Enter a string: \")<br>if text == text[::-1]:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(\"Palindrome\")<br>else:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(\"Not a palindrome\")<br> |
| **17** | Print numbers from 1 to 20 using `while` loop | <br>num = 1<br>while num <= 20:<br>&nbsp;&nbsp;&nbsp;&nbsp;print(num)<br>&nbsp;&nbsp;&nbsp;&nbsp;num += 1<br> |
| **19** | Calculate sum of digits of a number | <br>num = input(\"Enter a number: \")<br>sum_digits = sum(int(digit) for digit in num)<br>print(\"Sum of digits:\", sum_digits)<br> |

---

**✅ End of Document**

