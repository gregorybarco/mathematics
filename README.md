# Math 4701: Numerical Analysis
**Brooklyn College, City University of New York**  
**Gregory Barco** | [Portfolio](https://barcogregory.com/) | [GitHub](https://github.com/gregorybarco)

## Course Overview
This repository contains Maple implementations of fundamental numerical analysis algorithms studied in Math 4701. The course analyzes basic techniques for the efficient numerical solution of problems in science and engineering, spanning root finding, interpolation, approximation of functions, integration, differential equations, and direct and iterative methods in linear algebra.

## 📚 Course Information
- **Course**: Math 4701 (Numerical Analysis)
- **Credits**: 4 hours, 4 credits
- **Programming Language**: Maple (Computer Algebra System)
- **Semester**: Fall 2023

## 📁 Repository Structure

### 1. Error Analysis
- Floating point number representations
- Absolute and relative error calculations
- Round-off and truncation error analysis
- Remainder term applications in Taylor's formula

### 2. Interpolation and Polynomial Approximation
- **Lagrange Interpolation** - Polynomial fitting through data points
- **Newton Interpolation** - Divided difference approach
- **Hermite Interpolation** - Interpolation with derivative constraints

### 3. Solution of Nonlinear Equations
- **Bisection Method** - Root finding via interval halving
- **Fixed-Point Iteration** - Iterative approximation techniques
- **Aitken's Acceleration** - Convergence enhancement methods
- **Newton's Method** - Tangent-based root approximation

### 4. Numerical Differentiation and Integration
- Numerical differentiation of discrete data tables
- Function derivative approximation techniques
- Simple numerical integration formulas
- Composite integration methods
- Adaptive integration algorithms *(optional)*
- Romberg integration techniques *(optional)*

### 5. Initial-Value Problems for ODEs
- **Euler's Method** - First-order differential equation solving
- **Higher-Order Taylor Methods** - Enhanced accuracy approaches
- **Runge-Kutta Methods** - Multi-stage integration techniques
- **Predictor-Corrector Methods** *(optional)*

### 6. Linear Systems and Iterative Techniques
- **Gaussian Elimination** - Direct matrix solution methods
- **Cholesky Factorization** - Symmetric positive definite systems
- **Jacobi Iteration** - Parallel iterative solving
- **Gauss-Seidel Iteration** - Sequential iterative improvement
- **Cubic Splines** *(optional)*
- **Power Method for Eigenvalues** *(optional)*

## 🛠️ Technologies Used
- **Maple** - Primary computational environment
- **LaTeX** - Documentation and report generation
- **Git/GitHub** - Version control and collaboration

## 📖 How to Use This Repository

### Prerequisites
- Maple software (version 2022.2 or later recommended)
- Basic understanding of numerical methods
- Familiarity with mathematical computing concepts

### Running the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/gregorybarco/mathematics.git
   ```
2. Open Maple and navigate to the desired algorithm folder
3. Open the `.maple` files in Maple
4. Execute the worksheets to see the implementations in action

### File Organization
- Each algorithm includes:
  - **Maple worksheet** (`.maple`) - Implementation and examples
  - **PDF documentation** - Mathematical theory and results
  - **LaTeX source** (`.tex`) - Reproducible documentation

## 🎯 Learning Objectives
By the end of this course, students will be able to:
- Analyze and quantify computational errors in numerical algorithms
- Implement polynomial interpolation techniques for data approximation
- Solve nonlinear equations using various numerical methods
- Perform numerical differentiation and integration
- Solve ordinary differential equations numerically
- Apply direct and iterative methods to linear systems

## 📊 Algorithm Performance
Each implementation includes:
- **Convergence analysis** - Rate and conditions for convergence
- **Error bounds** - Theoretical and practical error estimates
- **Computational complexity** - Time and space requirements
- **Numerical examples** - Verification with known solutions

## 🤝 Contributing
This repository serves as a comprehensive reference for numerical analysis implementations. Feel free to:
- Report issues with existing implementations
- Suggest improvements to algorithms
- Add additional test cases or examples

## 📞 Contact
**Gregory Barco**  
Bachelor of Science in Mathematics  
Brooklyn College, CUNY  
- Portfolio: [barcogregory.com](https://barcogregory.com/)
- GitHub: [@gregorybarco](https://github.com/gregorybarco)

## 📄 License
This project is created for educational purposes as part of Math 4701 coursework at Brooklyn College.

---
*"The purpose of computing is insight, not numbers."* - Richard Hamming
