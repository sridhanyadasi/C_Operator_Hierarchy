# C Operator Hierarchy (Operator Precedence)

This repository explains Operator Hierarchy (Operator Precedence) 
in C programming with simple examples and clear understanding.

---------------------------------------------------------------

## 🔹 What is Operator Hierarchy?

Operator Hierarchy (also called Operator Precedence) 
defines the priority level of operators when multiple 
operators are used in a single expression.

👉 In simple words:
It decides which operation will execute first.

Example:
int result = 10 + 5 * 2;

Here, multiplication (*) has higher precedence than addition (+),
so 5 * 2 executes first.

🔹 Why is Operator Hierarchy Important?

Without hierarchy:

Expressions may give wrong results

Program logic may fail

Execution order becomes confusing

Operator hierarchy ensures:

✔ Correct calculation
✔ Proper execution order
✔ Clear understanding of expressions
✔ Avoid logical errors

🔹 Uses of Operator Hierarchy

Writing complex mathematical expressions

Writing conditional statements

Logical operations

Writing optimized code

Avoiding unnecessary parentheses

🔹 Order of Operator Precedence in C (High to Low)

Parentheses ()

Unary operators (++ -- ! sizeof)

Multiplication, Division, Modulus (* / %)

Addition, Subtraction (+ -)

Relational Operators (< <= > >=)

Equality Operators (== !=)

Logical AND (&&)

Logical OR (||)

Assignment Operators (= += -= *= /= %=)

🔹 Example

Expression:
int result = 10 + 5 * 2 - 4;

Execution Steps:

Step 1: 5 * 2 = 10
Step 2: 10 + 10 = 20
Step 3: 20 - 4 = 16

Final Result = 16

🔹 How to Control Hierarchy?

We can use parentheses () to change execution order.

Example:
int result = (10 + 5) * 2;

Here addition executes first.

🔹 Purpose of This Repository

✔ To clearly understand operator precedence
✔ To avoid confusion in complex expressions
✔ To practice execution step-by-step
✔ To strengthen C programming fundamentals
✔ To help students in exams and interviews

👩‍💻 Author

Sri Dhanya
