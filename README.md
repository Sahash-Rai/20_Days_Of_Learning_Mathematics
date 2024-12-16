# **Mathematical Foundations for Machine Learning: A 20-Day Exploration**
![Mathematics](https://github.com/Sahash-Rai/20_Days_Of_Learning_Mathematics/blob/main/Assets/Mathematics_For_ML.webp)
## 📂 Resources: Mathematics for Machine Learning  


| Topic                       | Resource Name                             | Link                                                                 |
|-----------------------------|-------------------------------------------|----------------------------------------------------------------------|
| **Linear Algebra**          | 3Blue1Brown YouTube Series                | [Watch Here](https://www.youtube.com/watch?v=kjBOesZCoqc)            |
|                             | Linear Algebra Cheat Sheet                | [PDF](https://mathworld.wolfram.com/topics/LinearAlgebra.html) |
| **Vectors and Matrices**    | NumPy Documentation                       | [Read Here](https://numpy.org/doc/stable/)                          |
|                             | Khan Academy: Vector Math                 | [Watch Here](https://www.khanacademy.org/math/linear-algebra)       |
| **Statistics**| Think Stats by Allen B. Downey           | [Read Book](https://greenteapress.com/wp/think-stats/)              |
| **Calculus**                | Paul’s Online Notes (Calculus)            | [Visit Here](http://tutorial.math.lamar.edu/)                       | 
|                             | Khan Academy: Calculus                    | [Learn Here](https://www.khanacademy.org/math/calculus-1)           
| **Optimization**            | Convex Optimization by Boyd and Vandenberghe | [Read Here](https://web.stanford.edu/~boyd/cvxbook/)                |
|                             | Gradient Descent Explained (YouTube)      | [Watch Here](https://www.youtube.com/watch?v=sDv4f4s2SB8)           |
| **General Math for ML**     | Mathematics for Machine Learning (Book)   | [Read Here](https://mml-book.github.io/)                            |
|                             | Essential Math for Data Science           | [Learn More](https://www.datacamp.com/courses/essential-math-for-data-science) |
|                             | Brilliant.org (Interactive Math Courses)  | [Start Here](https://brilliant.org/)                                |
- [**GeeksforGeeks**](https://www.geeksforgeeks.org/machine-learning/?ref=home-articlecards)

---


# Mathematics for Machine Learning - Day 1:
### Day 1: Linear Algebra Foundations 📐  
- **Topics Covered**:  
  - **Vectors**: Basics of vector operations (addition, dot product, scalar multiplication).  
  - **Matrices**: Matrix operations (addition, multiplication, transpose).  
  - **Identity & Inverse Matrices**.  
- **Key Learnings**:  
  1. Understanding vectors in n-dimensional space.  
  2. Importance of matrix operations in transforming data.  
  3. Inverse matrices used to solve linear systems.  
- **Code Implementation** 💻  
     Implemented vector and matrix operations using Python and NumPy.
  
  ![Day 1 Code Snapshot](https://github.com/Sahash-Rai/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_1.png)  

---

### Day 2: Determinants and Matrix Inverses 🧮  
- **Topics Covered**:  
  - **Determinants**: Determinant of a matrix and its geometric significance.  
  - **Inverse Matrices** (continued).  
  - **Eigenvalues & Eigenvectors**.  
- **Key Learnings**:  
  1. How determinants help determine the invertibility of a matrix.  
  2. The concept of eigenvalues and eigenvectors in linear transformations.  
  3. How to use determinants in machine learning model optimization.  
- **Code Implementation** 💻  
  Implemented determinant, matrix inversion, eigenvalue and eigenvector with examples.  
  ![Day 2 Code Snapshot](https://github.com/Sahash-Rai/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_2.png)
  
---

 ### Day 3: Advanced Matrix and Vector Operations 🚀
- **Topics Covered**:
  - **Scaling**: Adjusting the data's range for standardization or normalization.
  - **Vector Spaces**:  Concepts of spans, basis, and dimensions.
  - **Matrix Operations**: Dot products, multiplication, row space, and column space.
  - **Orthogonality**: Applications of orthogonal vectors.
  - **Projections**: Projecting vectors onto subspaces.
- **Key Learnings**:
  1. Scaling ensures consistent preprocessing for machine learning workflows.
  2. Vector spaces establish a foundation for understanding linear algebra.
  3. Orthogonality and projections are essential for dimensionality reduction.
  4. Matrix operations accelerate computations in higher dimensions.
- **Code Implementation** 💻  
    Implemented  scaling, vector operations, matrix products and projections using Python and NumPy.
   ![Day 3 Code Snapshot](https://github.com/SahashRaee/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_3.png)
  

---

### Day 4: Linear Transformations, LU Decomposition, and Matrix Rank 📊  

- **Topics Covered**:  
  - **Linear Transformations**: Applying transformations like scaling, rotation, and reflection using matrices.  
  - **LU Decomposition**: Factorizing a matrix into lower and upper triangular matrices to simplify solving linear systems.  
  - **Rank of a Matrix**: Understanding the number of linearly independent rows or columns in a matrix.  

- **Key Learnings**:  
  1. **Linear Transformations** help in transforming vectors by scaling, rotating, or reflecting them.  
  2. **LU Decomposition** helps in solving systems of linear equations efficiently and calculating determinants.  
  3. The **Rank of a Matrix** gives insight into the linear independence of the matrix's rows and columns.  

- **Code Implementation** 💻:  
  - **Linear Transformation**: Applied a matrix transformation to a vector using matrix multiplication.  
  - **LU Decomposition**: Decomposed a matrix into its lower and upper triangular matrices.  
  - **Matrix Rank**: Calculated the rank of a matrix to understand its linear dependence.
    ![Day 4 Code Snapshot](https://github.com/SahashRaee/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_4.png)

    ---
    ## Day 5: Advanced Linear Algebra Concepts 📐

**Topics Covered**:  
- **Diagonalization**  
- **Singular Value Decomposition (SVD)**  
- **Principal Component Analysis (PCA)**  
- **QR Decomposition**

**Key Learnings**:  
1. **Diagonalization**: Decompose a matrix into eigenvectors and eigenvalues.  
2. **SVD**: Factorize matrices into orthogonal matrices and singular values for dimensionality reduction and more.  
3. **PCA**: Used for reducing the dimensionality of data, retaining the most important features.  
4. **QR Decomposition**: Decomposes a matrix into an orthogonal and upper triangular matrix to solve linear systems.

**Code Implementation** 💻  
Implemented a class based approach for performing  linear algebra operations on matrices.

![Day 5 Code Snapshot](https://github.com/SahashRaee/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_5.png)

---
## Day 6: Advanced Matrix Operations & Decompositions 📐

### Topics Covered:
- **Diagonalization**: Process of diagonalizing a matrix using its eigenvalues and eigenvectors.
- **Principal Component Analysis**: Dimensionality reduction technique for high-dimensional datasets.
- **Singular Value Decomposition**: Factorizing a matrix into three components.

### Key Learnings:
1. **Diagonalization**: Understanding how to express a matrix as a product of eigenvectors, eigenvalues, and the inverse of the eigenvector matrix.
2. **PCA**: Applying PCA for reducing the dimensions of the dataset while preserving the variance.
3. **SVD**: Breaking a matrix into its singular values and vectors, with applications in compression, data reduction, and noise filtering.

### Code Implementation 💻
Implemented advanced matrix operations, including diagonalization, PCA, and SVD, to analyze and transform matrices using Python and libraries like NumPy and Scikit-learn.
![Day 6 Code Snapshot](https://github.com/SahashRaee/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_6.png)




---

#  Day 7: Probability Foundations 🎲  

- **Topics Covered**:  
  - Basics of probability: Events, sample space, and probability axioms.  
  - Conditional probability and Bayes theorem.  
  - Discrete and continuous distributions: Binomial and Normal.  

- **Key Learnings**:  
  1. Conditional probability helps to calculate the likelihood of an event given another event.  
  2. Bayes theorem is essential for updating probabilities based on new evidence.  
  3. Binomial distribution models discrete events, while the Normal distribution models continuous data.  

- **Code Implementation** 💻:  
  Implemented a concise structure to handle conditional probability, binomial PMF, and normal PDF with visualizations for better understanding.
  ![Day 7 Code Snapshot](https://github.com/SahashRaee/20_Days_Of_Learning_Mathematics/blob/main/Assets/20_Days_Code/code_day_7.png)

---
## Day 8: Probability Distributions and Bayes Theorem 🎲

### Topics Covered:
- **Bayes Theorem**: Formula for updating the probability of a hypothesis given new evidence.
- **Bernoulli Distribution**: Describes binary outcomes with one parameter for success probability.
- **Binomial Distribution**: A generalization of the Bernoulli distribution for multiple trials.

### Key Learnings:
- Bayes Theorem helps in updating beliefs with new data, essential in statistical inference and machine learning.
- Bernoulli Distribution models binary outcomes like success/failure.
- Binomial Distribution extends Bernoulli for multiple independent trials, useful in many classification and prediction tasks.

### Code Implementation 💻
Implemented Bayes Theorem, Bernoulli Distribution, and Binomial Distribution using Python and SciPy.

