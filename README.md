# Experiment 8
# Name: Pratyush Saha
# PRN: 24070123078
# Class: ENTC A3

# Title: Multidimensional arrays

Introduction to 2D Arrays (Multidimensional Arrays)
A 2D array is an array of arrays, often used to represent matrices or tables with rows and columns. It stores data in a grid-like structure, where each element can be accessed by two indices — one for the row and one for the column.

# Key points:

Declaration: int arr[rows][cols];
Access element at row i and column j: arr[i][j]
Useful for matrix operations like addition, multiplication, transpose, and diagonal summation.
Programs, Algorithms and Explanation
1. Taking and Displaying a Fixed Size (3x3) Matrix
Problem: Input and display a 3x3 matrix.

Algorithm:

Define matrix of size 3x3.
Input matrix elements.
Display matrix elements in row-column format.
Explanation:
Simple input-output of fixed-size matrix to practice basic 2D array handling.

2. Matrix Addition
Problem: Add two matrices of same dimensions.

Algorithm:

Input dimensions of both matrices (must be equal).
Input elements of both matrices.
Initialize result matrix.
Loop through all elements and add corresponding elements.
Display the resultant matrix.
Explanation:
Matrix addition is done element-wise and requires both matrices to have the same dimensions.

3. Matrix Multiplication
Problem: Multiply two matrices if number of columns in first matrix equals number of rows in second.

Algorithm:

Input rows and columns for both matrices.
Check if multiplication is possible (cols1 == rows2).
Input elements of both matrices.
Initialize result matrix to zero.
Multiply: for each element of result, sum products of row elements of M1 and column elements of M2.
Display the result matrix.
Explanation:
Matrix multiplication combines rows of the first matrix with columns of the second, producing a new matrix.

4. Matrix Transpose
Problem: Find transpose of a matrix.

Algorithm:

Input rows and columns.
Input matrix elements.
Create transpose matrix with swapped dimensions.
For each element (i,j), assign to transpose[j][i].
Display transpose.
Explanation:
Transpose flips rows and columns, which is used widely in matrix algebra and transformations.

5. Sum of Diagonal Elements of a Matrix
Problem: Calculate the sum of the main diagonal elements of a matrix.

Algorithm:

Input the number of the rows and columns.
Check if the matrix is square (rows == cols).
Input the matrix elements if it is a square matrix.
Initialize a sum variable to 0.
Loop through each row i and add the element at matrix[i][i] to the sum.
Output the sum.
Explanation:

The main diagonal of a matrix consists of elements where the row index and column index are the same (e.g., (0,0), (1,1), (2,2), ...). Summing these gives the diagonal sum.

# Conclusion
These programs demonstrate foundational matrix operations using 2D arrays in C++. Understanding how to manipulate 2D arrays is crucial for solving complex problems involving matrices, including those in graphics, simulations, and data processing.

About
