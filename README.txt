JavaScript Interview Questions and Answers

1. Why do we call JavaScript a dynamic language?
JavaScript is called a dynamic language because variable types are determined at runtime.

2. How does JavaScript determine data types?
JavaScript uses dynamic typing based on assigned values.

3. What is typeof?
typeof is an operator used to identify the type of a variable.

4. How to check data type in JavaScript?
Using:
- typeof
- instanceof
- Array.isArray()

5. What are different datatypes in JavaScript?

Primitive Types:
- String
- Number
- Boolean
- Undefined
- Null
- Symbol
- BigInt

Non-Primitive Types:
- Object
- Array
- Function

6. Explain Undefined Data Type
A variable declared but not assigned a value is undefined.

7. What is Null?
null represents an intentional absence of value.

8. Difference between Null and Undefined

Null:
- Intentional empty value
- Type is object

Undefined:
- Variable declared but not assigned
- Type is undefined

9. Explain Hoisting
Hoisting moves declarations to the top of scope during compilation.

10. Are JavaScript initializations hoisted?
No. Only declarations are hoisted, not assignments.

11. What are global variables?
Variables accessible throughout the application.

12. What are the issues with Global variables?
- Name collisions
- Security issues
- Memory leaks
- Difficult debugging

13. What happens when you declare variable without VAR?
It becomes a global variable in non-strict mode.

14. What is Use Strict?
"use strict" enables strict mode to avoid unsafe coding practices.

15. How to force developers to use Var keyword?
Use "use strict".

16. How can we handle Global Variables?
Using:
- Namespaces
- Modules
- Closures

17. How can we avoid Global variables?
- Use let and const
- Use modules
- Use IIFE
- Use closures

18. What are Closures?
A closure remembers variables from its outer scope.

19. Why do we need Closures?
- Data privacy
- State preservation
- Memoization
- Callbacks

20. Explain IIFE
Immediately Invoked Function Expression.

21. What is the use of IIFE?
- Avoid global scope pollution
- Create private scope

22. What is name collision in global scope?
When multiple variables/functions use the same global name.

23. IIFE vs Normal Function

IIFE:
- Executes immediately
- Creates private scope

Normal Function:
- Executes when called
- Reusable

24. What are design patterns?
Reusable solutions for common software problems.

25. Which is the most used design pattern?
Module Pattern.

26. What is Module Pattern and Revealing Module Pattern?

Module Pattern:
Hides private members.

Revealing Module Pattern:
Explicitly exposes selected members.

27. How many ways are there to create JavaScript objects?

- Object literal
- new Object()
- Object.create()
- Constructor function
- Class

28. How can we do inheritance in JavaScript?
Using prototypes and prototype chaining.

29. What is prototype in JavaScript?
An object from which other objects inherit properties.

30. Explain prototype chaining
JavaScript searches properties through linked prototypes.

31. What is let keyword?
let declares block-scoped variables.

32. Are let variables hoisted?
Yes, but they remain in Temporal Dead Zone until initialized.

33. Explain Temporal Dead Zone
The time between hoisting and initialization where accessing variable throws error.

34. let vs var

let:
- Block scope
- No redeclaration
- Supports TDZ

var:
- Function scope
- Allows redeclaration
- Hoisted with undefined

35. String concatenation and arithmetic puzzle

"5" + 2 = "52"
"5" - 2 = 3

+ performs concatenation when one operand is string.
- converts values to numbers.
