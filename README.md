# INTRODUCTION TO PROGRAMMING (Python)
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

## 05. Introduction to Lists (Python Data Structures)
### Overview
This module introduced Python lists as a fundamental data structure for organizing and manipulating collections of data. Lists enable efficient storage, retrieval, and modification of ordered elements and are central to data science workflows, including preprocessing, aggregation, and feature engineering.
The lesson emphasized why lists are preferable to raw strings for structured data representation, particularly in applied contexts such as computer vision classification tasks (e.g., organizing flower species labels for image classification).
### Key Concepts Covered
- **List creation and structure**
  - Defined lists using square brackets `[]`
  - Stored homogeneous data types (e.g., strings, integers) within a single list
  - Compared list-based data storage to unstructured string representations
- **List length and indexing**
  - Used `len()` to determine the number of elements in a list
  - Applied zero-based indexing to access individual elements
  - Retrieved first, last, and intermediate items reliably
- **List slicing**
  - Extracted subsets of lists using slice notation (`[:x]`, `[-y:]`)
  - Understood that slicing returns a new list rather than modifying the original
- **Modifying lists**
  - Removed elements using `.remove()`
  - Added new elements using `.append()`
  - Demonstrated dynamic updates to list contents
- **Lists with numeric data**
  - Worked with lists of integers to represent time-series data
  - Applied built-in functions: `min()`, `max()`, `sum()`
  - Computed averages using list slices and aggregation functions
---
### Applied Exercises
#### Menu Management (List Modification)
- Removed obsolete items from a restaurant menu
- Appended new items using list methods
- Reinforced in-place list mutation and method-based updates
#### Customer Analytics (Numerical Lists)
- Computed average customer counts for specific time windows
- Identified peak and lowest traffic days using `max()` and `min()`
- Used slicing to analyze subsets of monthly data
#### String-to-List Conversion
- Converted structured strings into lists using `.split()`
- Generated:
  - Alphabet lists from delimiter-separated strings
  - Structured address components from comma-separated values
- Demonstrated preprocessing techniques common in text analytics
#### Intro to List Comprehensions
- Created boolean lists from numerical ratings using list comprehensions
- Translated conditional logic into compact, readable expressions
- Computed proportions using boolean arithmetic (`True` = 1, `False` = 0)
#### Time-Series Growth Analysis
- Implemented a function to calculate percentage growth over time
- Applied index-based list access for historical comparisons
- Reinforced correct use of list indexing in real-world analytics scenarios
---
### Learning Outcome
By completing this module, I developed proficiency in using Python lists for structured data storage, transformation, and analysis. I gained hands-on experience with indexing, slicing, aggregation, and list comprehensions—skills that are foundational for data preprocessing, exploratory data analysis, and feature construction in data science and machine learning pipelines.
### Overall Outcome
This module strengthened my understanding of Python’s core data structures and their practical applications in analytics and modeling tasks. The ability to efficiently manipulate lists provides a critical foundation for working with larger datasets using libraries such as pandas, NumPy, and scikit-learn in subsequent projects.

---

# PYTHON (Detail)
### Lessons Overview
1. Hello, Python 
2. Functions and Getting Help  
3. Booleans and Conditionals
4. Lists
5. Loops and List Comprehensions
6. Strings and Dictionaries
7. working with external Libraries
---
## 001. Hello, Python (Syntax, Variables, and Numbers)
### Overview 
This module introduced Python fundamentals for numerical computation, variable handling, and basic arithmetic—essential skills for data science.
### Key Concepts
- **Variables & Assignment**: Store and update values dynamically (`spam_amount = 0; spam_amount += 4`)
- **Comments**: Use `#` for readability.
- **Printing & Functions**: `print()` displays output; `type()` checks variable type.
- **Strings**: Can be concatenated (`+`) or repeated (`*`).
- **Numbers & Arithmetic**: 
  - `int` and `float` types
  - Operators: `+`, `-`, `*`, `/`, `//`, `%`, `**`, `-a`
  - True division (`/`) vs floor division (`//`)
- **Order of Operations**: Follow PEMDAS; use parentheses to control precedence.
- **Built-in Functions**: `min()`, `max()`, `abs()`, `int()`, `float()`.
### Practical Exercises
- Calculate area of a circle
- Swap variables
- Use modulo to find remainders
- Apply parentheses to enforce operation order
### Learning Outcome
By completing this module, I developed additional foundational Python programming skills, including variable assignment, arithmetic operations, and basic problem-solving with numbers and strings. I learned to interpret code, predict outputs, and implement simple algorithms, which are essential skills for data manipulation and scientific computing in Python.
### Overall Outcome
This module laid the groundwork for future data science tasks, providing the basic numerical and programming literacy needed to progress to more advanced Python topics such as lists, loops, functions, and data analysis.
#### kaggle kernels output abrahamkadusei/exercise-syntax-variables-and-numbers -p /path/to/dest
---
## 002. Functions and Getting Help
### Overview
This lesson introduces Python functions as a fundamental tool for writing reusable, readable, and efficient code. It covers both built-in functions and user-defined functions, with emphasis on documentation, flexibility, and practical problem-solving.
### Key Concepts
- **Built-in functions and help()**  
  Used functions such as `print()`, `abs()`, and `round()`. Learned to use `help()` to understand function behavior, arguments, and defaults.
- **Defining custom functions**  
  Created functions using `def`, passed arguments, and returned values using `return` to avoid repetition and improve clarity.
- **Docstrings**  
  Added docstrings to describe function purpose and usage, making code self-explanatory and accessible through `help()`.
- **Return values vs side effects**  
  Distinguished between functions that return values and those that operate through side effects (e.g., printing output).
- **Default arguments**  
  Implemented optional parameters with default values to make functions more flexible and reusable.
- **Higher-order functions**  
  Explored passing functions as arguments and using built-in higher-order functions such as `max()` with the `key` parameter.
### Applied Practice
- Implemented rounding and utility functions
- Modified functions to accept optional parameters
- Debugged common function-related errors
- Applied functions to real-world style problems (e.g., candy sharing logic)
### Learning Outcome
By completing this lesson, I gained practical experience writing modular, well-documented Python functions and applying them flexibly—an essential skill for data analysis, scientific computing, and machine learning workflows.

