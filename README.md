# 00 – Introduction to Programming (Python)
### Lessons Overview
1. Arithmetic and Variables  
2. Functions  
3. Data Types  
4. Conditions and Conditional Statements  
5. Introduction to Lists  
**Notebook originally developed on Kaggle:**  
#### https://www.kaggle.com/code/abrahamkadusei/abkor-getting-started-with-titanic  
---
## 01. Arithmetic & Variables (Python Basics)
### Overview
This module introduces me to the foundational concepts of Python programming relevant to data science. Emphasis is placed on numerical computation, variable assignment, code readability, and basic debugging, skills essential for scalable data analysis and machine learning workflows.
### Key Concepts Covered
- **Output and display**  
  Utilized the `print()` function to display text, variables, and computation results.
- **Arithmetic operations**  
  Performed addition, subtraction, multiplication, division, and exponentiation while applying correct operator precedence (PEMDAS).
- **Code documentation**  
  Applied comments (`#`) to improve code clarity, readability, and maintainability.
- **Variable assignment and reuse**  
  Created, updated, and reused variables to support structured and interpretable computations.
- **Multi-variable calculations**  
  Combined multiple variables to perform extended calculations, such as estimating elapsed time across several years.
- **Introductory debugging**  
  Identified and corrected common syntax and runtime errors, including `NameError` caused by undefined or misspelled variables.
### Practical Example
A multi-step calculation was implemented to estimate the number of seconds in four years. This example demonstrated how variables support modular thinking, ease assumption updates (e.g., accounting for leap years), and improve computational transparency.
### Intro to Programming Exercise → First Kaggle Competition
### Overview
This exercise marked my transition from foundational Python syntax to applied data science in a Jupyter notebook environment. It emphasized confidence in executing code cells, interpreting outputs, and working with structured datasets.
### Applied Learning with Real Data
Using the **Titanic Kaggle dataset**, I:
- Explored passenger-level data using pandas
- Computed descriptive statistics (total passengers, survivors, minors)
- Calculated interpretable proportions such as survival rate and fraction of minors
### Transition to Competition Workflow
The exercise concluded with a guided submission to the Titanic competition, serving as a practical bridge between introductory programming and applied machine learning experimentation.
### Outcome
This module established my foundational Python competency and introduced the Kaggle ecosystem, providing a platform for iterative learning in data analysis and predictive modeling.
#### kaggle kernels output alexisbcook/arithmetic-and-variables -p /path/to/dest
---
## 02. Functions in Python
### Overview
This module focused on structuring Python code using functions to improve reusability, clarity, and computational efficiency. Functions were used to show me how to encapsulate logic and reduce redundancy in analytical workflows.
### Key Concepts Learned
- Defining functions using `def`
- Function parameters and return values
- Calling functions with varying inputs
- Writing reusable and modular code
- Understanding variable scope (local vs. global)
- Implementing functions with multiple or no arguments
### Practical Examples
- A simple arithmetic function demonstrating input–output mapping
- A function to compute weekly earnings after tax deductions
- A generalized payroll function accepting wage and tax parameters
- Demonstrations of scope limitations for variables defined within functions
### Learning Outcome
By completing this module, I developed the ability to write modular, reusable Python functions, an essential skill for building maintainable data pipelines and analytical models.
### Personal Practice: House Price Estimation
- Implemented a custom function to estimate housing costs using bedroom and bathroom counts
- Applied a baseline price with incremental cost logic
- Compared multiple housing options efficiently through repeated function calls
- Reinforced understanding of function arguments, return values, and abstraction
#### kaggle kernels output alexisbcook/functions -p /path/to/dest
---
## 03. Data Types (& Boolean Arithmetic)
### Overview
This module examined me on Python’s core data types i.e. integers, floats, booleans, and strings, and analyzed how they interact during arithmetic operations and within function logic.
### Key Concepts Practiced
- Identifying data types using `type()`
- Type conversion (e.g., `float` → `int`) and truncation behavior
- Distinction between positive and negative float truncation
- Boolean arithmetic (`True = 1`, `False = 0`)
- String operations including concatenation, repetition, and length evaluation
### Applied Practice
- Investigated arithmetic interactions between booleans and numeric data types
- Evaluated boolean behavior when applied to strings
- Built a house price estimation function incorporating boolean features (e.g., presence of a basement)
- Implemented conditional pricing logic using boolean multiplication instead of explicit `if` statements
- Designed a real-world pricing function for engraved rings based on material type and engraving length
### Learning Outcome
This module strengthened my understanding of Python’s type system and demonstrated how boolean arithmetic can simplify conditional logic. These principles are fundamental to writing clean, efficient, and expressive code for data analysis, feature engineering, and modeling workflows.
reuse
- Practiced applying programming logic to a real-world, competition-inspired scenario
#### kaggle kernels output abrahamkadusei/exercise-data-types -p /path/to/dest
