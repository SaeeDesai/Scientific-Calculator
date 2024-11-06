# Scientific-Calculator 🧮

Welcome to the **Scientific-Calculator**—a comprehensive, command-line calculator for performing a wide range of mathematical and scientific computations. This tool is designed to handle everything from basic arithmetic to complex equations, making it perfect for students, educators, and enthusiasts!

---

## Features 📋

### 1. Basic Arithmetic ➕➖✖️➗
- Perform **addition**, **subtraction**, **multiplication**, and **division**.
- Quick and simple operations for everyday calculations.

### 2. Trigonometry 📐
- Supports **Sine, Cosine, Tangent**, and their **inverse functions** (arcsin, arccos, arctan).
- Choose between **degrees** and **radians**.

### 3. Matrix Operations 🧊
- Works with **2x2 matrices**:
  - **Addition** and **Subtraction**
  - **Multiplication**
  - **Determinant** and **Transpose**
- Ideal for linear algebra applications.

### 4. Quadratic Equation Solver 📈
- Solves equations of the form \( ax^2 + bx + c = 0 \).
- Supports both **real** and **complex roots**.

### 5. Simultaneous Equations Solver 🔗
- Solve **two-variable** and **three-variable** linear equations.
- Uses elimination and substitution methods.

### 6. Permutations & Combinations 🎲
- Calculates **permutations (nPr)** and **combinations (nCr)**.
- Useful for probability, combinatorics, and statistics.

---

## Getting Started 🚀

### Prerequisites

To run this calculator, you’ll need:
- **C++ Compiler** (e.g., GCC)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Math_Science_Calculator
2. **Compile and Run**:
   ```bash
   g++ calculator.cpp -o calculator
   ./calculator

## Using the Calculator 🧑‍💻

- **Main Menu**: The program prompts you to select an operation. Enter the corresponding number.
- **Input Values**: Follow prompts to enter values such as matrix elements, coefficients, or angles.
- **Results**: The calculator displays results instantly.
- **Repeat Option**: After each calculation, choose 'y' or 'Y' to continue or any other key to exit.

---

## Usage Guide 📝

Here’s how to use some of the features:

### Example 1: Solving a Quadratic Equation

1. Select the **quadratic equation** option from the main menu.
2. Input values for **a**, **b**, and **c**.
3. The calculator displays the roots, including **complex solutions** if applicable.

### Example 2: Solving Simultaneous Equations

1. Choose the option for **two-variable** or **three-variable** equations.
2. Enter coefficients and constants for each equation.
3. Displays solutions or notifies if no unique solution exists.

---

## Code Structure 🛠️

- **Classes**: Each functionality is encapsulated within its own class for modularity:
  - `Simultaneous` for simultaneous equations
  - `PandC` for permutations and combinations
- **Factorial Calculation**: Uses recursion for factorials, essential for combinations and permutations.

---

## Future Enhancements 🌟

We have several exciting features planned for future versions of this calculator. Below are some of the ideas:

### 1. Expanded Matrix Support for Larger Matrices
- The current implementation supports only basic 2x2 and 3x3 matrices. Future versions will handle larger matrices and provide operations such as matrix multiplication, inverse, and determinant calculation for any size matrix.

### 2. Graphical User Interface (GUI)
- A user-friendly GUI will be developed using frameworks like **Qt** or **Tkinter**, allowing users to interact with the calculator through buttons and text fields, making it more intuitive and accessible.

### 3. Additional Equation Types and Complex Operations
- The calculator will support solving higher-order polynomial equations, systems of nonlinear equations, and other advanced mathematical functions.
- Operations such as **integration**, **differentiation**, and solving **differential equations** are also in the pipeline.

### 4. Improved Error Handling
- Future versions will feature better error handling for invalid inputs, edge cases, and division by zero errors, providing users with more helpful error messages and guidance.

### 5. Customization and User Preferences
- Users will be able to customize their experience by selecting preferred settings for mathematical precision, units (degrees/radians), and color themes in the GUI.

### 6. Performance Optimization
- As the complexity of the operations increases, performance optimization will be prioritized to ensure that the calculator remains fast even for larger datasets and calculations.



