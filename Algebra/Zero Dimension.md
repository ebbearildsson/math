#algebra 
#linear-algebra 
## Definition
## Methods
1. Calculation
For any equally sized matrix $A$ which has a [[Rank]] less than its size, calculate its [[Upper Right Matrix]] and then calculate for which values $Ax=0$: $$
\begin{align}
\begin{bmatrix}a & b & c \\ 0 & e & f  \\ 0 & 0 & 0\end{bmatrix}
\begin{bmatrix}x_{0} \\ x_1 \\ x_2 \end{bmatrix}=
\begin{bmatrix}0 \\ 0 \\ 0 \end{bmatrix}\\
x_{2}=t, t\in\mathbb{R}\\
ex_{1}+ft=0\rightarrow x_{1}=-\frac{f}{e}t\\
ax_{0}+b(-\frac{f}{e}t)+ct=0\rightarrow x_{0}=-\frac{b(-\frac{f}{e}t)+ct}{a}=-\frac{-\frac{bf}{e}+c}{a}t\\
dim_{0}=t(1,-\frac{f}{e},-\frac{-\frac{bf}{e}+c}{a})
\end{align}$$ 