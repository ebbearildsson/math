#algebra 
#linear-algebra 
## Definition
A method for creating a [[Upper Right Matrix]] from a any equally sized [[Matrix]]. 
## Methods
1. General
$$ \begin{bmatrix}a&b&c \\ d&e&f \\ g&h&i\end{bmatrix}$$
$$ \begin{bmatrix} a&b&c \\ d-a\cdot\frac{d}{a}&e-b\cdot\frac{d}{a}&f-c\cdot \frac{d}{a} \\ g-a\cdot\frac{g}{a}&h-b\cdot\frac{g}{a}&i-c\cdot \frac{g}{a}\end{bmatrix} $$
$$\begin{bmatrix} a&b&c \\ 0&e-b\cdot\frac{d}{a}&f-c\cdot \frac{d}{a} \\ 0&h-b\cdot\frac{g}{a}&i-c\cdot \frac{g}{a}\end{bmatrix} $$
$$ \begin{bmatrix} a&b&c \\ 0&e-b\cdot\frac{d}{a}&f-c\cdot \frac{d}{a} \\ 0&h-b\cdot\frac{g}{a}-(e-b\cdot\frac{d}{a})\cdot\frac{h-b\cdot\frac{g}{a}}{e-b\cdot\frac{d}{a}} & i-c\cdot\frac{g}{a}-(f-c\cdot\frac{d}{a})\cdot\frac{h-b\cdot\frac{g}{a}}{e-b\cdot\frac{d}{a}}\end{bmatrix} $$
$$ \begin{bmatrix} a&b&c \\ 0&e-b\cdot\frac{d}{a}&f-c\cdot \frac{d}{a} \\ 0&0 & i-c\cdot\frac{g}{a}-(f-c\cdot\frac{d}{a})\cdot\frac{h-b\cdot\frac{g}{a}}{e-b\cdot\frac{d}{a}}\end{bmatrix} $$


