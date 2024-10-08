<h1>Aim</h1>
<p>To study and implement C++ 2D array and matrices.</p>
<hr>
<h1>Thoery</h1>
<p>C++ two-dimensional (2D) arrays, or matrices, are a way to store data in a grid-like structure with rows and columns. They allow efficient storage and access to data, making them ideal for mathematical computations, simulations, and handling tabular data. Each element is accessed using two indices, representing its position within the matrix.</p>
<hr>
<h1>Algorithms</h1>
<h2>Addition of two matrices</h2>
<ol>
  <li>Start.</li>
<li>Input Matrix Dimensions:
<ul>
<li>Enter rows (r1) and columns (c1) for the first matrix.</li>
<li>Enter rows (r2) and columns (c2) for the second matrix.</li>
</ul>
</li>
<li>Check Matrix Compatibility:
<ul>
<li>If r1 == r2 and c1 == c2, proceed.</li>
<li>Otherwise, display "Addition cannot be performed".</li>
</ul>
</li>
<li>Input Matrix Elements:
<ul>
<li>Initialize matrices a[r1][c1] and b[r2][c2].</li>
<li>Enter elements for the first matrix into a[i][j].</li>
<li>Enter elements for the second matrix into b[i][j].</li>
</ul>
</li>
<li>Calculate Matrix Sum:
<ul>
<li>Initialize sum[r1][c1].</li>
<li>For each element, calculate sum[i][j] = a[i][j] + b[i][j].</li>
</ul>
</li>
<li>Output the Result:
<ul>
<li>Display the resulting sum matrix.</li>
</ul>
</li>
  <li>End</li>
</ol>
<br>
<h2>Matrix Multiplication</h2>
<ol>
  <li>Start.
<li>Input Matrix Dimensions:
    <ul>
    <li>Enter the number of rows (r1) and columns (c1) for the first matrix.</li>
    <li>Enter the number of rows (r2) and columns (c2) for the second matrix.</li>
    </ul>
</li>
<li>Check Matrix Multiplication Feasibility:
    <ul>
    <li>If c1 (columns of the first matrix) is not equal to r2 (rows of the second matrix), display "Matrix multiplication is not possible" and terminate.</li>
    </ul>
</li>
<li>Initialize Matrices:
    <ul>
    <li>Declare and initialize matrix A of size r1 x c1.</li>
    <li>Declare and initialize matrix B of size r2 x c2.</li>
    <li>Declare matrix C of size r1 x c2 and initialize all its elements to 0.</li>
    </ul>
</li>
<li>Input Matrix Elements:
    <ul>
    <li>For matrix A, input each element and store it in A[i][j].</li>
    <li>For matrix B, input each element and store it in B[i][j].</li>
    </ul>
</li>
<li>Perform Matrix Multiplication:
    <ul>
    <li>For each element 'c[i][j]' in the resulting matrix:
    <ul>
      <li>Compute c[i][j] as the sum of products of corresponding elements from rows 'i' of first matrix and columns 'j' of second matrix</li>
    </ul>
    </li>
    </ul>
</li>
<li>Output the Result:
    <ul>
    <li>Print the resultant matrix C.</li>
    </ul>
</li>
  <li>End.</li>
</ol>
<br>
<h2>Reverse Diagonal Sum of a Matrix</h2>
<ol>
  <li>Start.</li>
  <li>Initialise i,j,r,c.</li>
  <li>Prompt the user to enter no. of rows and columns and store it in 'r' and 'c'.</li>
  <li>Check for square matrix: If r is not equal to c, print "Matrix is not a sqaure matrix" and terminate.</li>
  <li>Else, initialise 2D matrix arr[r][c].</li>
  <li>Run two loops and take input elements of the matrix from the user and terminate the loops.</li>
  <li>Run two loops and print the matrix in grid format.</li>
  <li>Calculate sum of the reverse diagonal elements
  <ul>
    <li>Initialise sum to 0.</li>
    <li>Start loop.</li>
    <li>Access element of diagonals using arr[i][r-i-1] and add it to sum.
    </li>
    <li>Terminate Loop.</li>
  </ul>
  </li>
  <li>Display sum.</li>
  <li>End.</li>
</ol>
<hr>
<h1>Conclusion</h1>
<p>
The experiment with C++ 2D arrays and matrices enhances understanding of multi-dimensional data handling. By learning matrix operations and element manipulation, we improve our programming skills and problem-solving abilities, essential for various applications in computing and data analysis.</p>
