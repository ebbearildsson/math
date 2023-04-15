#algebra 
#linear-algebra 
## Definition
The [[Vector Space]] spanned by the [[Matrix]]'s [[Coloumn]]s.
> Often written as either rank(A), rk(A) or rank A. (Where A is a matrix).
## Method 
1. [[Gaussian Elimination]]
By performing a gaussian elimination one can simply count how many of the [[Eigenvalues]] are nonzero.
$$
\begin{align*}
rank
\begin{pmatrix}
\begin{bmatrix}
a & 0 & 0\\
0 & b & 0\\
0 & 0 & 0
\end{bmatrix}
\end{pmatrix}
=2
\end{align*}
$$
2. [[Zero Dimension]]
The rank can be found by calculating the differance between the matrix's [[Dimension]] and zerodimension, $dim(A) - dim_0(A)$.
## Example
1. Fixed Rank
Calculate all numbers $a$ can be so that, rank $A=0$, where $A$ is:$$
\begin{align}
\begin{bmatrix}1 & -1 & 2\\2 & 0 & -1\\-1 & 3 & a\end{bmatrix}\\
\begin{bmatrix}1 & -1 & 2\\0 & 2 & -5\\0 & 2 & a+2\end{bmatrix}\\
\begin{bmatrix}1 & -1 & 2\\0 & 2 & -5\\0 & 0 & a+7\end{bmatrix}\\
a+7=0\\
a=-7
\end{align}
$$