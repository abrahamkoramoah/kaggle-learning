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
---
## 04. Conditions & Conditional Statements
### Overview
This module introduced conditional logic in Python, enabling programs and functions to adapt their behavior based on input values. Conditional statements are fundamental for decision-making in data processing, rule-based systems, and real-world modeling tasks.
### Key Concepts Covered
- **Boolean conditions**  
  Evaluated expressions that resolve to `True` or `False` using comparison operators (`<`, `<=`, `>`, `>=`, `==`, `!=`).
- **Conditional control flow**  
  Used `if`, `if–else`, and `if–elif–else` statements to control which blocks of code are executed.
- **Indentation and code blocks**  
  Applied correct indentation to define logical execution scopes within functions and conditionals.
- **Order of evaluation**  
  Learned that conditional checks are evaluated sequentially and that the order of `elif` statements affects program output.
- **Conditional calculations**  
  Used conditions not only to assign messages, but also to perform different numerical computations based on thresholds.
### Practical Examples
- Evaluated body temperature to classify outcomes (normal, fever, low temperature)
- Calculated tax obligations under different income brackets
- Implemented dosage determination using multiple conditional thresholds
- Demonstrated how a single function can return different outputs based on input ranges
### Learning Outcome
By completing this section, I developed the ability to write Python functions that respond dynamically to input data—an essential skill for data validation, business logic, and decision-driven analytics.
## Applied Exercise: Conditional Logic in Real-World Scenarios
This exercise applied conditional statements to realistic data scenarios, reinforcing logical reasoning and structured decision-making in Python.
### Tasks Completed
- **Grade classification system**  
  Converted numerical exam scores into standardized letter grades using ordered `elif` conditions.
- **Conditional pricing logic**  
  Reimplemented an engraving cost estimator using `if–else` statements for material-based pricing decisions.
- **Tier-based billing systems**
  - Calculated water bills based on usage tiers and per-unit pricing
  - Computed mobile data charges with base plans and overage fees
- **Complex condition evaluation**
  - Interacted with externally defined functions to assess nutritional thresholds
  - Generated health warning labels based on multiple independent conditions
### Key Skills Demonstrated
- Translating policy rules into executable logic
- Implementing tiered pricing and threshold-based decisions
- Reading and using externally defined functions without full implementation details
- Applying clean, readable conditional structures to non-trivial problems
### Learning Outcome
This exercise strengthened my ability to implement robust conditional logic for applied data problems. The scenarios mirror real-world use cases in admissions systems, billing platforms, public health policy, and regulatory decision tools—highlighting the importance of clear logic and correct condition ordering in applied programming.
### Overall Outcome
By completing this module, I gained practical experience designing decision-driven Python functions. These skills are directly applicable to data preprocessing, rule-based modeling, feature engineering, and analytical pipelines commonly used in data science and machine learning workflows.
#### kaggle kernels output abrahamkadusei/exercise-conditions-and-conditional-statements -p /path/to/dest
