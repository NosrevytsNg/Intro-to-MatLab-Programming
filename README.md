# 🧠 MATLAB Programming Exercises

A collection of **MATLAB programs developed as part of introductory numerical computing and programming coursework**.  
This repository demonstrates fundamental MATLAB concepts including **mathematical computation, algorithm implementation, input validation, and data visualisation**.

The programs were implemented using MATLAB and tested through the MATLAB Online environment.

## Project Overview

This repository documents three MATLAB programming tasks designed to develop familiarity with the MATLAB environment and numerical scripting techniques.

The programs cover three key areas:

- Mathematical computation using loops and vector operations
- Interactive data visualisation using MATLAB plotting functions
- Algorithm implementation for real-world data validation

Together, these exercises demonstrate how MATLAB can be used to build **interactive scripts, perform calculations, and generate graphical insights from data**.

## Programs Included

### 1. Geometric Progression Summation

This program calculates the summation:

\[
\sum_{n=5}^{M} (2^{n-2} + (n+2))
\]

The user is prompted to input the value **M**, and the program computes the total sum for values of **n ranging from 5 to M**.

#### Key Concepts Demonstrated

- MATLAB user input handling
- Loop iteration
- Exponential arithmetic operations
- Accumulating values using iterative summation
- Formatted output using `fprintf`

#### Example Output

```text
Please insert value of M: 10
M = 10 and the sum = 561
```


---
# 5️⃣ Smart Plotter Program

```markdown
### 2. Smart Plotter Application

The **Smart Plotter** is a menu-driven MATLAB program that allows users to interactively generate graphs from datasets and mathematical functions.

#### Main Menu

```text
1) Plot the relationship between Days and Sales
2) Plot f(x), g(x), f(x)*g(x), and f(x)/g(x)
3) Quit the Smart Plotter
```

---

# 6️⃣ Days vs Sales Plotting

```markdown
#### A. Days vs Sales Data Visualisation

The program loads numerical data from external files and visualises the relationship between **days and sales**.

Supported graph types:

- Bar chart
- Scatter plot
- Line graph

Each graph includes:

- axis labels
- title
- computed **total sales value**

Example annotation displayed on graphs:

```text
Total Sales: 550
```


---

# 7️⃣ Function Plotting

```markdown
#### B. Mathematical Function Plotting

The program also plots the following functions over the range:

\[
x \in [-1, 1]
\]

Functions plotted:
f(x) = x + 3
g(x) = x^2 + 1
f(x) * g(x)
f(x) / g(x)
```

Graph types supported:

- Scatter plot
- Line graph

All functions are displayed on the same figure using MATLAB plotting tools with legends for comparison.

#### Concepts Demonstrated

- anonymous functions
- multi-series plotting
- interactive menus
- figure customisation
- legend and axis configuration



### 3. Singapore NRIC Checksum Validator

This program implements an algorithm used to compute the **checksum character of a Singapore NRIC number**.

Example NRIC format: S1234567X


Where:

- `S` or `G` represents the category of the holder
- the final character `X` is the checksum letter

#### Algorithm Steps

1. Validate the first letter (`S` or `G`)
2. Validate that the numeric portion contains exactly **seven digits**
3. Multiply digits in odd positions by **3**
4. Add digits in even positions
5. Compute the total modulo **11**
6. Determine the checksum character using a lookup table

#### Example Execution

```text
Enter the first letter of your NRIC (S or G): S
Enter your seven-digit NRIC number: 2307605
Your NRIC is: S2307605F
```

Concepts Demo:
- input validation
- string manipulation
- modular arithmetic
- conditional logic
- algorithm implementation



---

# 9️⃣ Example Visualisations

```markdown
## Example Visualisations

The Smart Plotter program generates multiple graph types.

Examples included in this repository:

- Days vs Sales bar chart
- Days vs Sales line graph
- Days vs Sales scatter plot
- Mathematical function line graphs
- Mathematical function scatter graphs

These examples demonstrate MATLAB’s built-in plotting capabilities for exploratory data analysis.
``` 

Each implementation folder contains:

- screenshots of the MATLAB scripts
- command window outputs
- generated graphs

This documentation-based structure preserves the original development environment even though the MATLAB `.m` files are not included.


## MATLAB Concepts Demonstrated

This project demonstrates several fundamental MATLAB programming concepts:

- interactive scripts
- vector operations
- loop-based calculations
- menu-driven programs
- file-based data loading
- mathematical function plotting
- graphical visualisation
- algorithmic validation of structured identifiers

## Learning Outcomes

Through these exercises, the following programming skills were developed:

- understanding MATLAB syntax and script structure
- implementing numerical algorithms
- designing interactive command-line applications
- visualising datasets using MATLAB plotting tools
- building validation algorithms using conditional logic

These exercises provide a foundational understanding of MATLAB for **scientific computing and numerical programming**.


## Technologies Used

- MATLAB (MATLAB Online Environment)

## Author

**Styverson Ng**

This repository forms part of my personal GitHub portfolio showcasing coursework and practical exercises in programming, data analysis, and computational problem solving.
